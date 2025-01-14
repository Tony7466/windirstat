# WinDirStat - Windows Directory Statistics

## Description

WinDirStat is a program that allows you to find drive space hogs at a glance. It achieves that by displaying a drive, drives or directories in a [treemap](https://en.wikipedia.org/wiki/Treemap) that assigns bigger areas to bigger files and directories. Making those areas visually separate by coloring and other means allows you to see literally at a glance what the space hogs are and where to dig deeper.

![image](https://github.com/user-attachments/assets/d22de6b5-c292-497d-a0da-c4c7c2a10eae)


The directory tree is simultaneously shown as a tree list and as a treemap. One can effortlessly gain an impression of the proportions on the drive(s).

For more information on the background of WinDirStat and alternative versions on other operating systems, please visit the [WinDirStat website](https://windirstat.net/)

### Major features

* Three views: Directory Tree, Treemap, and Extension
* Duplicate file detection
* Built-in cleanup actions including Open, Delete, Show Properties
* User-defined cleanup actions (command line based)

For changes in recent versions, please check out [the change log](CHANGELOG.md).

### Installation

* 📦 Install it by downloading the appropriate version for your system from the [release page](https://github.com/windirstat/windirstat/releases/)
  * 📦 Install with `winget install -e --id WinDirStat.WinDirStat` (or use `winget upgrade` subsequently)
  * 📦 Alternatively install with `scoop install extras/windirstat` (requires `scoop bucket add extras`)

## Copyright / Licenses

* Copyright © WinDirStat Team ([windirstat.net](https://windirstat.net/))

The application itself is distributed under the terms of the [GPL v2](windirstat/res/license.txt), but parts of the source code are also available under more lenient license terms.

*Note:* you are not at liberty to upgrade the GPL version to anything later than v2 at this moment.

The logo and all derivatives are available under the terms of the Creative
Commons license [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).

## Building

WinDirStat can be built with Visual Studio 2022 or later. A Visual Studio solution file can be loaded from `windirstat\WinDirStat.sln`.

## Contributing

You can contribute by responding to issues, developing source code, or developing translations.

To see a list of contributors, please check out [the contributors page](CONTRIBUTORS.md).

## Compatibility

WinDirStat 2.x has been developed for and tested on the following operating systems. They may work on older or newer operating systems but are not supported.

* Windows 7
* Windows 8
* Windows 8.1
* Windows 10
* Windows 11
* Windows Server 2008 R2
* Windows Server 2012
* Windows Server 2012 R2
* Windows Server 2016
* Windows Server 2019
* Windows Server 2022
* Windows Server 2025

## Logo

![WinDirStat logo](windirstat/logos/logo_256px.png)

The logo was generously designed and contributed to the project by Robin "tuqueque" Marín. Follow him on Twitter/X [@tuquequeorg](https://twitter.com/tuquequeorg).

## Alternatives

If you are looking for other opensource alternatives to WinDirStat for Windows or other operating systems, please checkout the links below. If you'd like your opensource project to be added to this list, please contact us.

MacOS: [GrandPerspective](https://grandperspectiv.sourceforge.net/)

Linux: [QDirStat](https://github.com/shundhammer/qdirstat)

Windows: [SpaceSnipper](https://github.com/redtrillix/SpaceSniffer)

## Downloads
[Intel 64-Bit MSI Installer](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat-x64.msi)

[Intel 32-Bit MSI Installer](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat-x86.msi) 

[ARM 64-Bit MSI Installer](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat-arm64.msi)

[ARM 32-Bit MSI Installer](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat-arm.msi)

[Zipped Executables](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat.zip)

[Zipped Executables (7-Zip)](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat.7z)

[File Hashes](https://github.com/windirstat/windirstat/releases/download/release/v2.2.0/WinDirStat-Hashes.txt)

You may also install it with:

📦 winget install -e --id WinDirStat.WinDirStat (or use winget upgrade subsequently)

📦 scoop install extras/windirstat (requires scoop bucket add extras)


## Community

* [Website](https://windirstat.net/)
* [Blog](https://blog.windirstat.net/)
* Twitter/X as [@windirstat](https://x.com/windirstat)
* SubReddit [r/WinDirStat](https://www.reddit.com/r/WinDirStat/)

Find a more up-to-date list of resources on the [website](https://windirstat.net/) and the [blog](https://blog.windirstat.net/) at any point in time.
