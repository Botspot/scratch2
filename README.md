# Scratch 2

Install Scratch 2 back on the latest Raspberry Pi OS. Scratch 2 was removed after Adobe Flash was discontinued. Fortunately, this repository makes it easy to install back.  
However, as this is an offline application, it is still safe [and legal ](https://web.archive.org/web/20200421061947/https://www.google.com/intl/en/chrome/terms/) to use it.

## To install
[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)  
Or, to install manually:  
**PLEASE ONLY INSTALL THIS ON RASPBERRY PI OS 32-BIT!!** Installing it on a 64-bit OS will remove a many packages and may cause issues.
```
git clone https://github.com/Botspot/scratch2
sudo apt install ~/scratch2/scratch2_0.25_armhf.deb
rm -rf ~/scratch2
```
Scratch 2 package was originally acquired from [the official archive page](http://archive.raspberrypi.org/debian/pool/main/s/scratch2/). A few files have been rearranged to make it more portable and less likely to cause any overwrite conflicts.    
