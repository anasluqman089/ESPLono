---
title: "ESPLono"
github: "https://github.com/anasluqman089/ESPLono"
description: "A devboard build around an ESP32 S3 ICs with built in connector for camera and SD card storage."
created_at: "2026-11-01"
total_time: "2h 30m"
---

# November 2, 2026: ENTRY - 1 : Built the Schematic
<!-- fabricate:entry 1840 -->

_Hello Everyone!_

Today, I did the the Schematic. It is pretty confusing but some guide and youtube videos, I managed to finished it but I dont know if its right.

![](https://fabricate.hackclub-assets.com/6e1d15914e6b3a36246027c5e31d39c686571b1c91a2d06f2e785e7e937eb415/image-png/image.png)

![](https://fabricate.hackclub-assets.com/063440224d953d79f38915539b8f695fe1110a3f0bdebd814736dfa94f5a5443/image-png/image.png)

As the description said, I used an ESP32 S3 but more specifically an ESP32-S3 Wroom-1 RF Modules. It has 24 pin FPC connector for an OV camera and a Micro SD card reader. I also added a TP4056 for LiP-Po battery charging and an APK2112k for 5V. 

I have already know the design I want to use and that is a Raspberyy Pi Zero look, so it will have that 02xXX pin header. But dues to having so many thing, there is not much pin so I split to four section. 

1. GND, 3V3, 5V and GPIO (02x05)
![](https://fabricate.hackclub-assets.com/5a19d09f394422082ad19726b80002d7353ba42112309594c66c443211f15d3f/image-png/image.png)


2. I2C (02x04)
![](https://fabricate.hackclub-assets.com/7222e703226476303bb6ba576cc7ca70408703c6afafa446f4fd6fa0c1317c4f/image-png/image.png)

3. SPI (01x06)
![](https://fabricate.hackclub-assets.com/09d738ab14269bca57d9a403afcd9bc4974c0321b1f05234a16b134d947c19b5/image-png/image.png)

4. UART (01x04)
![](https://fabricate.hackclub-assets.com/095239959b4b7c13f7d8de45fad7fd9187e40864b00a4d8a82d57237197e5cca/image-png/image.png)

That is all for today, If you can please give me any feedback on slack @anasluqman089

**Total time spent: 2h**

# November 3, 2026: Entry 2 - PCB USB and Charging
<!-- fabricate:entry 2080 -->

_Hello everyone_

Today i have finished with the **USB and charging area** of the PCB! It was very stresfull because it is my first time doing this. I dont really know the widht of trace should be so for 5V i used 4mm and the signal will use 2mm. I havent connected the ground and cc because I will do it tomorrow.

![](https://fabricate.hackclub-assets.com/4b608c0903a201f09672d40757aa24bcdfe084835994556d79d896b63c82cc3b/image-png/image.png)

As you can see, the orange plane is the 5V plane. I have been doing for half a hour and I cant continue doing it.

That is all for today!

**Total time spent: 30m**
