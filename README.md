# Hackintosh ROG strix z490

## Hardware

* **Motherboard**: Asus Rog Strix Z490-H Gaming
* **CPU**: Intel Core i7-10700K
* **Memory**: HyperX Fury, 32GB (2x16GB), 3000MHz, DDR4
* **GPU**: Gigabyte AMD Radeon RX 5600 XT Gaming OC
* **SSD**: Samsung 970 EVO Plus 250GB, M.2 NVMe

## Software

* Bootloader: OpenCore 0.6.0-RELEASE
* OS: macOS Catalina 10.15.7

## What's working

- [x] Audio Realtek ALCS1220A  
- [x] Intel I225-V 2.5Gb Ethernet  
- [x] USB  
- [x] Restart/Shutdown  
- [x] Sleep/Wake  
- [x] Power Management  
- [x] AMD Radeon RX 5600XT  
- [x] Intel UHD Graphics 630

## Not working

* Netflix, Amazon Prime playback in Safari. But works with other browsers like Chrome, Firefox, Brave
* GPU Temperature

## Bios

**Disable**

* Fast Boot
* CSM
* Intel SGX

**Enable**

* Above 4G decoding
* Hyper-Threading
* EHCI/XHCI Hand-off
* OS type: Other OS
* DVMT Pre-Allocated(iGPU Memory): 64MB
