# ASRock Z370M-ITX/ac macOS Catalina
A working clover configuration for ASRock Z370M-ITX/ac
Inspired from heisian's configuration:<br>
https://github.com/heisian/Z370M-ITX-AC-macOS

## macOS version
`10.15.4 (19E266)`

## Note for people using iGPU or Sidecar
Intel UHD 630 device ID is different in some CPUs so you might need to change the device ID according to your CPU.<br>
Example:
```
i7-8700K (UHD 630)        = 0x3E928086
i3-8100  (UHD 630)        = 0x3E918086
```
See more at: https://ark.intel.com/content/www/us/en/ark

## System Specs
* Motherboard: ASRock Z370M-ITX/ac
* CPU: Intel i7-8700K 3.7GHz
* RAM: Unknown brand 24GB (8GB and 16GB) DDR4-2400 Memory
* Storage: Samsung EVO Plus 970 500GB + Seagate 2TB 7200RPM HDD
* GPU: AMD Sapphire RX570 4GB + Intel UHD 630
* PSU: Corsair SF 450W 80+ Gold Certified Fully-Modular SFX Power Supply
* Wifi + BT: BCM94360CS2 with adapter

## Post-install
* SmUUID and Serial Number generation for iMessage. Search the forums!

## Optional
* Turn iGPU dual monitor on in BIOS to use Sidecar with AMD GPU or any other compatible external GPU

## Working
* Dual GPU (EGPU + iGPU)
* APFS
* Ethernet
* Sleep (Note: Automatically wakes up for few seconds and sleeps back itself)
* Audio
* NVMe SSD
* Sidecar (You may need compatible Wifi and Bluetooth module and working iGPU)

The motherboard's built-in Bluetooth and Wifi module does NOT work with macOS.
You will need to get a compatible module for the M.2 slot, or use a USB
Bluetooth dongle.

## Issues or Bug reporting
Make an issue if you find a bug or a problem specifically for this hardware. Also if you found the solution, pull requests are welcome!
