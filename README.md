# Legion-Y7000-Hackintosh-Opencore
This is an efi that i used for my Lenovo Legion Y7000 2019 PG0. Big sur is a WIP, and i will be updating it as i go.

## My laptop specs

 - Processor - Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz
 - Memory - 16 GB DDR4 RAM
 - Wireless - Intel(R) Wireless-AC 9560 160MHz
 - Storage - ST1000LM049-2GH172 - 931.51 GBs
 - Storage - WDC PC SN730 SDBPNTY-256G-1101 - 238.47 GBs
 - Graphics - Intel UHD 630, GTX 1650 (Disabled)
 - Keyboard - Ps/2
 - Trackpad - I2C


Im currently running windows on my ssd and (later on) macos on a partition on my data drive (hard drive)

## Installation Guide

Use [Dortina's Opencore guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) to make the USB.
Once you're done with that, just delete the EFI folder and 'boot' on the USB and replace it with the one provided in 'Legion Hackintosh' and boot off the USB.

## Updates

**Update - October 16 2020**

Ive booted into the installer. For some reason the ethernet isnt working. To be fixed.

**Update - October 17 2020**

I fixed ethernet and am now booted into catilina. Also added itlwm.kext for intel internet. There is a .dmg for "heliport". Run that when you're booted into catilina.

**Update - October 17 2020**

ive fixed nearly everything on catilina (except trackpad, not going to use xosi cause its gonna break windows booting)
Big Sur Eta S0n (ill be starting work on big sur)

ill be posting the final release for catilina soon. 
