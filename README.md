# tl-wn823n-v2
Modified driver for the TP-LINK TL-WN823N-V2 WiFi module that works with the BeagleBone Black.

The driver was originally downloaded from [here](http://www.tp-link.com/us/download/TL-WN823N.html#Driver).

Modifications were made to allow compilation against the BeagleBone Black kernel 4.1.13-ti-r36.  In particular, the following file was modified:

```
Driver/os_dep/linux/rtw_cfgvendor.c
```

A kernel module compiled against the 4.1.13-ti-r36 kernel on a BeagleBone Black is availabe at:

```
Driver/bin/8192eu.ko
```
    
