# platform-rock64

**Volumio platform files for Pine Inc. Rock64 Boards**

Kernel Sources  
http://github.com/ayufan-rock64/linux-kernel  
U-boot Sources  
http://github.com/ayufan-rock64/linux-u-boot  

**Still Work-In-Proress, more info to be supplied....**  

This version is not using the rockchip kernel and u-boot repos yet.  
Ayufan's repo is a number of critical commits ahead (audio patches by kwiboo).    

For more ino on platform files, see https://volumio.github.io/docs/Porting_Guide/Introduction.html    

This repo contains all files, used by the Volumio Builder to create a **Rock64** image  

- kernel files (kernel, modules, firmware)  
- u-boot  
- other files. e.g. kernel configuration etc.  

**Changelog**

2017.09.07  Beta version  

2018.07.20  Added RT5370 wireless support  

2018.09.29  Kernel upgrade, remains work-in-progress  

- Upgraded to Ayufan's kernel 4.4.138+ 
- Replaced u-boot by rockchip master  
- Added support for a range of additional wireless adapters  

2018.10.03	Kernel update

- Included support for CONFIG_OF_CONFIGFS  
- Included script for enabling DT_OVERLAY  

2018.12.31	Kernel update

- USB Audio: add support for a wide range of DSD-direct capable DACs
- USB-Audio: Eliminate noise at the start of DSD playback







 


 
