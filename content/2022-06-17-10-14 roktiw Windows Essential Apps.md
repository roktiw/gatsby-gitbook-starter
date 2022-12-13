---
title: "2022-06-17-10-14 roktiw Windows Essential Apps"
metaTitle: "2022-06-17-10-14 roktiw Windows Essential Apps "
metaDescription: "2022-06-17-10-14 roktiw Windows Essential Apps
---

# What to do or install after installing Windows 10 

## ESSENTIAL - step by step

### Chocolately
Command line package installer

[https://chocolatey.org/](https://chocolatey.org/install)

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
From now on install almost all apps using Chocolately

List all packages installed by Choco
```
choco list --local-only
```

Update all packages installed by Choco
```
choco upgrade all
```


### Google Chrome
Web browser from Google

[https://www.google.com/chrome/](https://www.google.com/chrome/)

```
choco install googlechrome
```


### Adguard
Block Ads systemvide (in every Web Browser and app) - Get rid of mindmelting all around you advertising.

https://adguard.com/

You have to install it by downloading package. Installing from Choco did not work for me.

Note to self: is there AdGuard alternative: app just for simple filtering the HTTP/HTTPS request using the open source lists


### 7zip
Package manager for .zip, .rar files. It is open source under GNU LGPL licence - so better than winrar.

[https://www.7-zip.org/](https://www.7-zip.org/)

https://community.chocolatey.org/packages/7zip

```
choco install 7zip
```


### VLC Media Player

[https://www.videolan.org/vlc/
](https://www.videolan.org/vlc/)

https://community.chocolatey.org/packages/vlc

```
choco install vlc
```


### CCleaner
Program to maintain clean Windows install.

https://www.ccleaner.com/

https://community.chocolatey.org/packages/ccleaner

```
choco install ccleaner
```


### Google Drive
There is no cloud it's just someone else's computer.

https://www.google.com/drive/

https://community.chocolatey.org/packages/googledrive

```
choco install googledrive
```


### windirstat
Visually identify huge files and folders. It is GNU GPL compared to TreeSize. Support FLOSS software!

https://windirstat.net/

https://community.chocolatey.org/packages/windirstat

```
choco install windirstat
```

### f.lux
Blue light buster.

https://justgetflux.com/

https://community.chocolatey.org/packages/f.lux

```
choco install f.lux
```

### AutoDark Mode
Swithces automatically Windows theme betwiin Light and Dark

https://github.com/AutoDarkMode/Windows-Auto-Night-Mode

https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435

Set up hours for ```Night Light``` in Windows 10


### Dynamic Theme
It is essential because seing everyday new jungles, cities or panoramas gets me into good mood.

https://apps.microsoft.com/store/detail/dynamic-theme/9NBLGGH1ZBKW

### Microsoft Power Toys
https://apps.microsoft.com/store/detail/microsoft-powertoys/XP89DCGQ3K6VLD

---

## Plywood - Work

### Fusion360
```
choco install autodesk-fusion360
```

### Vcarve
https://www.vectric.com/products/vcarve-pro


---

# Tweaks

## Taskbar
Move on top.

It is better to by default look up not down.


## Menu Start
Remove all icons from right panel using `uninstall` if possible.

Remove all unnecessary apps.


## Taskbar

### Turn off
Cortana

Search Icon


### Pin to Taskbar
Settings

Microsoft Store

PowerShell

Windows Explorer

Fusion360

Vcarve

Google Chrome


## System Tray

### Always showa all icons


## NON ESSENTIAL

### Rufus - USB Creator
Burn ISO with Windows to USB key pendrive.

https://rufus.ie/en/

https://community.chocolatey.org/packages/rufus

```
choco install rufus
```

### Text editor
1. Visual Studio Code https://code.visualstudio.com/
2. Microsoft Word https://www.microsoft.com/en-ww/microsoft-365/word
3. LibreOffice https://www.libreoffice.org/

### Graphics
1. GIMP https://www.gimp.org/
2. Inkscape https://inkscape.org/

### Recording Audio
1. Audacity https://www.audacityteam.org/

### Desktop sharing
1. TeamViewer https://www.teamviewer.com/en/

### Clipboard
1. Ditto https://ditto-cp.sourceforge.io/

### Hot Corners like in Mac OS
winXcorners https://github.com/vhanla/winxcorners

### Utilities
HWINFO64

### VPN
Nord VPN

OpenVPN

VireGuard

### File Transfer
FileZilla

Transmission

### Disk analyzer
windirstat


## Windows 10 Tweaks

### Remove Cortana
```Get-AppxPackage -allusers Microsoft.549981C3F5F10 | Remove-AppxPackage```

### ADHA - Blac and White Windows
For ADHD remove colours with key combination

1. Color Filters
2. On
3. Allow the shortcut ```crtl win c``` 

### Windows10Debloater
https://github.com/Sycnex/Windows10Debloater
