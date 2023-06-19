# KakaoTalkAdBlock - .NET Fixed Version

AdBlocker for the Windows client of the chat software "KakaoTalk".

## Download

- Download the installer [setup.exe](https://github.com/LokeYourC3PH/KakaoTalkAdBlock-NETFIX/releases)
- Run `setup.exe` in order to install the Adblocker.
- After the installation, run `KakaoTalkAdBlock` from the Start Menu or Desktop.
- You may also register the software to start automatically when your System starts. 

### Requirements

- [.NET Framework 4.6.2 Runtime](https://dotnet.microsoft.com/download/dotnet-framework/net462)

### When uninstallable on Windows 10 due to security issues

#### Automatic fix
- Download [win10-security-fix.reg](https://github.com/blurfx/KakaoTalkAdBlock/blob/master/win10-security-fix.reg)
- Run `win10-security-fix.reg` to fix registry automatically

#### Manual fix
- Run Registry Editor by typing regedit in the run menu.
- Move to "\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\\\.NETFramework\Security\TrustManager\PromptingLevel"
- Change "Internet, Localintranet, MyComputer" to Enabled

## Update History

- Go [Releases](https://github.com/blurfx/KakaoTalkAdBlock/releases) page 

## At a glance

![](https://raw.githubusercontent.com/blurfx/KakaoTalkAdBlock/master/kakaotalk.png)

This program runs in the tray.

![](https://raw.githubusercontent.com/blurfx/KakaoTalkAdBlock/master/tray.png)
