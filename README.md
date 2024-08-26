## Intel NUC12  Extreme hackintosh OpenCore EFI

![image](ScreenShot/NUC12.JPG)

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 1.0.1](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x
- macOS Sonoma   14.x

### Hardware

- Motherboard: Intel Corporation NUC12EDBv9
- Bios Version: EDADLMIV.0062.2024.0305.1535  03/05/2024
- CPU: Intel 12th i9-12900
- RAM: Lenovo 16GB（8GB*2） DDR4 3200Mhz
- SSD: KINGBANK KP230
- iGPU: Intel UHD Graphic 770 (Only work in Windows)
- GPU: PowerColor AMD Radeon RX6600XT 8GB GDDR5
- Audio: Intel Alder Point-S PCH - HD Audio
- Ethernet Card: Intel L225-LM
- Ethernet Card: Marvell AQtion 10Gbit
- WIFI: Intel Wi-Fi 6E AX211

### Notes

 - Use [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) build your SMBIOS

### Bios Setup

```
Security
   |-- Secure Boot
      |-- Secure Boot ：Disabled 
      
   |-- Security Features
      |-- Intel VT for Directed I/O (VT-d) ：Enabled
      
  I can't remember the other options ^_^
```



### Known Issues

NUC12 Extreme Restart after sleep （may be something wrong with the BIOS settings）

### Contact Us

QQ Group: 23304408

![image](ScreenShot/QRCode.png)


### Tools

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.
