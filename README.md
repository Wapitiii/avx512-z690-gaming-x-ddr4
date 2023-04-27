# avx512-z690-gaming-x-ddr4
Enables AVX-512 instruction set - rename .fd to gigabyte.bin on a FAT32 usb stick and flash with Q-Flash button on motherboard afterwards.

## Requirements
* A 12th-Gen Intel CPU that has P-Cores with AVX-512 (For more information how to find out if your CPU has it, [Click here](https://github.com/zingaburga/alderlake_avx512/wiki))


## Instructions

* Download the modified BIOS
* Extract it and rename the .fd file to "gigabyte.bin"
* Put it onto a FAT32 USB Stick.
* Plug the USB Stick into the "Flash" USB Port on the motherboard.
* Press the Q-Flash Button on your motherboard. (This will erase your BIOS configuration, backup it before proceding!)
* Wait for a few minutes, until the LED stops flashing.
* Go into the BIOS and restore (if you made a backup) your settings, and disable your E-Cores.
* Boot into Windows normally and check via CPU-Z if you have the AVX-512 instruction set.

## Misc

If you want to patch it yourself, you can follow this guide:
https://github.com/thanghn90/gigabyte-avx512-bios-mod
