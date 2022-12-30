#EZ-FLASH Omega Definitive Edition Kernel

--------------------------------------
Korean font
Galmuri11 (https://galmuri.quiple.dev)

Differences from Original Kernel
1. Chinese changed to Korean
2. FatFs 0.15 version updated
3. Corrected a broken first word error when Filename_loop function with long Korean file name
--------------------------------------

### How to build 

    1.you can use latest version of devkitARM.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under winodws. If it goes well, you will get ezkernelnew.gba
    4.Double click on  Link_kernel_image.exe link the ezkernelnew.gba and image.bin to ezkernelnew.bin, that is the omegaDE kernel upgrade file
