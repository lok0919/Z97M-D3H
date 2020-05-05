# GA-Z97M-D3H macOS 10.15.4 (19E287) Opencore 0.5.8

## System Specs

- CPU: Intel Core i7-4790
- Motherboard: Gigabyte GA-Z97M-D3H
- Memory: 16GB (2 x 8GB) Kingston DDR3 2400MHz
- GPU: Sapphire Nitro+ Radeon RX 580 8G

## Prerequisites

- [ProperTree](https://github.com/corpnewt/ProperTree): For editing the config, this editor has some super useful tools for OpenCore
- [MaciASL](https://github.com/acidanthera/MaciASL/releases): For compiling SSDTs

## Creating the USB

Follow the [guide](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) to create a bootable USB

## Prepare config.plist for Haswell

Follow the [guide](https://dortania.github.io/OpenCore-Desktop-Guide/config.plist/haswell.html) to prepare the config.plist

## Note

I need to enable CSM in bios in order to see the OpenCore boot menu when using RX 580 + HDMI
