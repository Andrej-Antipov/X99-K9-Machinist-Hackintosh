# X99-K9-Machinist-Hackintosh
EFI Clover and OpenCore Folders and Workaround for Darkwake issue on X99 K9 Machinist mainboard for Mac OS. Also workaround for sleep/wake with PMDrvr.kext (better speedstep driver) on the latest mac os (Big Sur, Monterey, Ventura). Bluetooth hang on after wake fixed also.

## Hardware configuration:
* CPU: E5-2666v3 Haswell-EP
* MB: X99 K9 v2 Machinist
* Chipset: C216
* RAM: 4x8Gb DDR4 2666 Crucial Desktop
* GPU: Radeon RX 560 Sapphire Pulse 4Gb
* GPU: Radeon RX6600 PowerColor Fighter 8Gb
* SSD: 512Gb Kingstone KC2500 NVME M2
* SSD: 256Gb Kingspec NE-256 SATA M2
* HDD: 1Tb Hitachi 3.5" 7200 SATA
* WIFI/BT: bcm943602CS in M2 A/E keys NGFF adapter
* BIOS: https://github.com/BIOS-iEngineer/MACHINIST-X99ZV102
* Display: LG 4K 60 Hz HDR via Display Port (27UK650-W)

### Modes

* Fixed SmartFAN issue after wake with Ultimate Patcher Tool
* Unlocked turbobust for all cpu threads with S3TurboTool
* Undervolting -70/-50 cpu/cache
* flashed by afudos

### BIOS setup: 

* XHCI set to SmartAuto
* EFI only load

### Mac OS Big Sur, Monterey and Ventura EFI loaders.

* All mac os futures are working including DRM playback and sleep/wake S3
* Darkwake HID issue fixed with WakeUpScr applet. 
* Monterey Bluetooth wake issue fixed with WakeUpScr applet.
* Darkwake, Bluetooth, PMDrvr.kext wake issue fixed with WakeUpWithPMDrvr (PMDrvr_X99K9_ManageSet)
