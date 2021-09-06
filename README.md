**Raspberry PI 4 Monero Mining**

## Hardware

* [Rasppberry PI 4 8Go](https://www.kubii.fr/cartes-raspberry-pi/2955-raspberry-pi-4-modele-b-8gb-0765756931199.html)
* [Official power supply](https://www.kubii.fr/14-chargeurs-alimentations-raspberry/3292-alimentation-officielle-raspberry-pi-4-51-v-30-a-usb-type-c-prise-us-644824914893.html)
* [Argon One Case](https://www.amazon.fr/gp/product/B086JXR75B)
* A micro SD card Class 10
* A USB key

## Kernel

You need to build and run an optimized Kernel with Huge Page support.

I provided one here [on a Github repository](https://github.com/kraoc/raspberry-linux-64) with readme in *raspberry* folder.

## Miner

I use Xmrig with custom build options.

I provided one here [on a Github repository](https://github.com/kraoc/raspberry-xmrig-64) with readme in *raspberry* folder.

## Prerequisites

You must assemble your Pi inside the case with functionnal fan and run [Argon One Daemon](https://gitlab.com/DarkElvenAngel/argononed).

This daemon provide cli to monitor and update settings on the fly.

It's a good option to install & run [RPi-Monitor](https://github.com/XavierBerger/RPi-Monitor) to keep eyes on the beast.
