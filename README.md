# opencore-inspiron-3459
Opencore version patch 0.9.4 set for DELL Inspiron 14 3000 (3459 Skylake U)
tested on `High Sierra - Bigsur 11.6``

Note: `Bug touchpad, Wifi AR9565 (low and auto disconnect) and disabled SDCARD (not supported)`

## Requirements
For MAC
[Opencore Configurator](https://mackie100projects.altervista.org/download/opencore-configurator-2-73-0-0/) 2.73.0

For Windows or Linux
[Python 3](https://www.python.org/downloads/)
[ProperTree](https://github.com/corpnewt/ProperTree) - Needed installed Python 3 latest

## Specification:
- [x] Codeboard `[ Iris SKL 14236-1 CPWWO REV: AOO ]` Fix
- [x] CPU `Intel Core i5-6200U Skylake U 2 Core 4 Thread` Fix
- [x] Graphics `Intel HD Graphics 520 (Read 1500 MB)` Fix
- [x] Network `LAN RTL8100 + Wireless AR9565 + Bluetooth` Fix
- [x] Sound `ALC` Fix
- [x] Ram `Dual Channel 2x8 GB` Fix
- [x] Fan `Fan and Thermal` Fix with smc Needed App support for control
- X Graphics Switch `AMD Radeon R5 M315` Not Support but...
- X Touchpad `Synaptics` bug (idk this problem my touchpad or kext)
- ? Display Port `HDMI` Not tested
- ? Battery `Battery Status` Not tested

## Usage
Step: `Copy Folder "EFI" to your partition EFI (don't replacement. please delete first your old EFI)`

## Log
- version v5.7.0
- based: [Opencore RELEASE `0.9.4`](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.4)

## Disclaimer

This tools for help easywork and not for ilegal activity.

## License

Kucing Poi - [Salinku.xyz](https://salinku.xyz/)
GNU General Public License v3.0. See [LICENSE](https://github.com/piterpicek/EFI_14092023_14_3459_i5_6200U_AMD_M315_OC_094/blob/main/LICENSE)
