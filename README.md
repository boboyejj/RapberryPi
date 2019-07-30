# RaspberryPi
A tutorial for Raspberry Pi 4

## Device Introduction
If you want to upgrade your rpi3 to rpi4, remember to double check the new features! Don't be like me who knew nothing about the new rpi and cannot even boot it up when I received my new toy.

### USB-C Power
Now rpi4 doesn't use USB power supply anymore. Instead, it's now using **USB-C** power connector. Luckily, I found my macbook charger (29 W) suprisingly boot it up. However, rpi is sensitive to the power supply. Some users fails to boot their deives up by using macbook charger. So it's better to get one for it.

### Micro HDMI
Wait, my HDMI cannot fit the port on the rpi4 anymore! Fine... I would just wait a few more days for the Micro HDMI connector.

### 8GB Micro SD Card
For the new device, it needs at least 8 GB SD card. Or you can choose to install the operating system without the desktop. 

## Setup
- install os
After preparing all the supply, we can start setup the rpi4. 
1.  Download the os image from https://www.raspberrypi.org/downloads/ \
  If your SD card's capacity is larger than 8GB, download the Raspbian Buster with desktop and recommended software image.
  Otherwise, download the Raspbian Buster Lite image which only contains the command line without any GUI. 
  I am using the Lite version \
2.  Download Etcher from https://www.balena.io/etcher/ \
  Etcher helps write the image to your SD card. It supports Windows, Mac, and Linux.
3.  Plug in SD card to your computer
4.  Open Etcher -> select image you download -> select the SD card -> start to flash!
5.  After flashing drive successfully, plug SD card in rpi4, and connect to power and monitor. You will see the red light is on which means the device is up. When you see a flashing green light, it means it is reading the image.\
------------------------------ Following only for Raspbian Buster Lite --------------------------------
6.  Wait the system start and login\
  The default username:pi\
  Psw: raspberry
7.  Connect to Wifi
    1. sudo raspi-confi
    2. Select Network Options
    3. Select N2 Wi-fi
    4. Enter SSID (Default Wireless Network name) -> Ok
    5. Enter Passphrase -> Finish
  
- transfer files

## Cmd Line
ifconfig

