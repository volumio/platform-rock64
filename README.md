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

- Upgraded to Ayufan's kernel 4.4.132+, adding more wireless support  
- Replaced u-boot by rockchip master  
- Added support for a range of additional wireless adapters  




 


 
