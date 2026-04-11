# Hackintosh for Ryzen 3 2200G + RX 570 + ASUS B450M-A-II  
**macOS Tahoe 26.4** - OpenCore EFI

---

## System Specifications

| Component      | Details                          |
|----------------|---------------------------------|
| CPU            | AMD Ryzen 3 2200G               |
| GPU            | Radeon RX 570 4GB               |
| Motherboard    | ASUS B450M-A-II                 |
| RAM            | 12GB DDR4 2666MT/s              |
| Storage        | 128GB NVMe SSD (macOS), SATA SSD + HDD (Windows dual boot) |

---

## Overview

This is my Hackintosh setup running macOS Tahoe 26.4 on AMD Ryzen 3 2200G with Radeon RX 570 graphics, using the OpenCore bootloader. This repo contains my working EFI folder, config, and required kexts for this hardware configuration.

---

## What Works

- **CPU:** Full functionality with AMD Ryzen kernel patches  
- **GPU:** Radeon RX 570 hardware acceleration and Metal support  
- **Audio:** Built-in audio doesn't work while using AppleALC. Using external DAC for Audio  
- **USB:** All the USB ports are functional  
- **Other:** System updates, iMessage etc
---

## What Doesn’t Work / Known Issues
- **Sleep Issues:** Sleep doesn't work with Tahoe. Not fixing it either :-)

---

## References

- OpenCore Vanilla Guide: https://dortania.github.io/OpenCore-Install-Guide/  

---

## Screenshot

![Hackintosh Setup Screenshot]<img width="1920" height="1080" alt="ss" src="https://github.com/user-attachments/assets/cd977be5-3015-4b15-a963-fd01384578ba" />


*Last Updated: April 2026*

