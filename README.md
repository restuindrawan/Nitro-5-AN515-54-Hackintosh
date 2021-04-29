# Acer Nitro 5 AN515-54 Hackintosh

#### Supports MacOS 10.15.x ~ 11.x.x

![Screen Shot 2021-04-12 at 10 12 52 PM](https://user-images.githubusercontent.com/57904667/114408781-5a001f80-9bdc-11eb-8406-87852d82b836.png)

## My System
- Intel® Core™ i7-9750H
- Intel® UHD Graphics 630 & Nvidia GeForce® GTX 1650
- LG 1920x1080 15,6" 144Hz IPS Panel
- Broadcom DW1820A (Originally ship with Intel® Wi-Fi 6 AX200)
- 16gb 2666mHz of DDR4 RAM
- Samsung EVO 860 256gb M.2 (Originally ship with Micron 2200 256gb PCIe® NVMe™)
- Realtek HD Audio ALC255
- ELAN 0504 Touchpad
- BIOS Version 1.33

## Important Note
- THIS IS ILLEGAL USE IN PERSONAL ONLY!!!
- DWYOR!!!
- Enjoy it while we still can do this
- Set SATA mode to AHCI (Use CTRL+S in BIOS to unhide SATA Mode menu)
- Disable Secure Boot
- Generate new SMBIOS [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- Fix the CFG-Lock for Better Power Management [Dortania](https://dortania.github.io/OpenCore-Desktop-Guide//extras/msr-lock)

## Instalation Guide
- Soon... if you need :v

## What's Working:
- [x] Audio, Input/Mic, Output & [ComboJack](https://github.com/hackintosh-stuff/ComboJack)
- [x] iGPU with disabled dGPU
- [x] Battery Management
- [x] ACPI Display brightness with hot keys / slider
- [x] Ethernet
- [x] Sleep & Wake
- [x] WebCam
- [x] Usb 3.1 & Type C (Mapped USB)
- [x] WiFi & Bluetooth by using Broadcom DW1820A (Mine Requiring some Pin Shield)
![DW1820A_Cover_pins](https://user-images.githubusercontent.com/57904667/114368863-68384680-9bb0-11eb-9336-d6e6822293f3.jpg)
- [x] Native hotkey support with Fn keys
- [x] Touchpad and gestures
- [x] System Update

## Not Working:
- HDMI due to the port hardwired
- Nvidia GeForce® GTX 1650 (No Hope....)
- Intel® Wi-Fi 6 AX200 (Work in Progress) [OpenIntelWireless](https://github.com/OpenIntelWireless)
- Micron 2200 256gb PCIe® NVMe™ (Incompatible) to disable use "nvme=-1" boot-argument

## Credits
- **Special Thanks** to [dortania](https://dortania.github.io/vanilla-laptop-guide) for the vanilla laptop guide.
- **Special Thanks** to [Acidanthera](https://github.com/acidanthera) for most of the Kexts.
- Thanks to [OpenCore Bootloader](https://https://github.com/acidanthera/OpenCorePkg).
- Thanks to [daliansky](https://github.com/daliansky) for [ACPI Hotpatch Samples for the OpenCore Bootloader](https://github.com/daliansky/OC-little).
- Thanks to [alexandred](https://github.com/alexandred) for [VoodooI2C](https://github.com/alexandred/VoodooI2C).
- Thanks to [hackintosh-stuff](https://github.com/hackintosh-stuff) for [ComboJack support for ALC255](https://github.com/hackintosh-stuff/ComboJack).
- Thanks to [corpnewt](https://github.com/corpnewt) for [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).
