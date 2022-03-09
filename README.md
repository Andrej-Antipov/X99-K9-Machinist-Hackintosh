# X99-K9-Machinist-Hackintosh
EFI Clover and OpenCore Folders and Workaround for Darkwake issue on X99 K9 Machinist mainboard for Mac OS. 

## Hardware configuration:
* CPU: E5-2666v3 Haswell-EP
* MB: X99 K9 v2 Machinist
* Chipset: C216
* RAM: 4x8Gb DDR4 2666 Crucial Desktop
* GPU: Radeon RX 560 Sapphire Pulse 4Gb
* SSD: 512Gb Kingstone KC2500 NVME M2
* WIFI/BT: bcm943602CS in M2 A/E keys NGFF adapter
* BIOS: https://github.com/BIOS-iEngineer/MACHINIST-X99ZV102

### Modes

* Fixed SmartFAN issue after wake with Ultimate Patcher Tool
* Unlocked turbobust for all cpu thread with S3TurboTool
* Undervolting -70/-50 cpu/cache
* flashed by afudos

### BIOS setup: 

* XHCI set to SmartAuto
* EFI only load

### Mac OS Big Sur and Monterey config EFI

* All mac os futures are working including DRM playback and sleep/wake S3
* Darkwake HID issue fixed with WakeUpScr applet. 
* Monterey Bluetooth wake issue fixed with WakeUpScr applet.
* Darkwake, Bluetooth, PMDrvr.kext wake issue fixed with WakeUpWithPMDrvr (PMDrvr_X99K9_ManageSet)
