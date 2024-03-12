# Opencore HP Zbook 15 G2
This is an Opencore EFI repository of my HP Zbook 15 G2. **DISCLAIMER:** I will not be held responsible for any damage, permanent loss of data or any sorts of consequences that may arise by using my configuration files on your devices. Please use at your own risk.

## Current Release
- Opencore 0.9.8
- macOS Ventura 13.6.5
- All latest kexts as of March 10, 2024

## Notebook Specifications

| Specification  | Model |  Remark  |
| ------------- | ------------- | ------------- |
| Chipset  | Mobile Intel QM87 | M70 v01.26 (3/3/2020)  |
| CPU  | Intel i7-4810MQ  |
| iGPU  | Intel HD4600  | Intel (R) vBios 5.5.1028  |
| dGPU  | Nvidia Quadro K2100M  | Working with OCLP Post-Install
| Storage  | Crucial SATA 2.5 256GB (UpgradeBay) macOS | Axiom C560 SATA 2.5 Windows 10
| RAM  | 16GB (8x2GB) Micron PC3L |
| Ethernet  | Intel I217-LM  |
| Wi-Fi  | DW1560 - BCM94352Z  |
| Bluetooth  | BCM20702A0   |
| Audio  | Realtek ALC3228 (ALC280)   |
| Touchpad  | Synaptic SMBus Touchpad   |
| Inputs  | HP PS2 KB & Mouse  |

## What's working
- Mostly everything
- Wi-Fi & toggle button, Bluetooth, Ethernet
- Battery readouts
- Screen brightness adjustment
- Keyboard backlight
- Speakers, headphone jack, microphone, volume adjustments keys, sound toggle button
- USB ports
- HP Camera
- Sleep/wake
- dGPU  | Nvidia Quadro K2100M (with OCLP Post-Install)
- AppleID and iServices
- Displayport

## What's not working/issues
- Airdrop only received, not sent from Hackintosh (smooth on big sur)

## Not tested
- VGA port
- Thunderbolt port 
- SD Card reader

## Bios Settings
- Disable **Fast Boot**
- Enable **USB device boot**
- Set Boot Mode to **UEFI Hybrid (With CSM)**
- Device Configurations
  - Enable **Fn Key switch**
  - Enable **USB 3.0 (XHCI)**
  - Video memory size **64 MB**
  - SATA Device Mode: **AHCI**
  - Enable **Virtualization Technology (VTx)**
  - Disable **Virtualization Technology for Directed I/O (VTd)**
  - Disable **Trusted Execution Technology**
  - Enable **Intel(R) HT Technology**
  - Enable **Hybrid Graphics**
- Built-in Device Options
  - Enable **Wireless Button state**
  - Enable **Embedded Bluetooth Device**
  - Enable **Embedded LAN Controller**
  - Disable **Wake on LAN**
- Port Options
  - Disable **Serial & Parallel port**

## Credits
- All credits & rights goes to the maintainers, contributors and developers of the Opencore project and respective kernel extensions.
- Apple Inc.
