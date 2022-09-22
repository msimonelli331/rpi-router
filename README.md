# rpi-router
Steps and artifacts to help deploy a wifi rpi router

## OpenWRT
We will use OpenWRT as our router firmware. It will be configured as a wifi bridge. The purpose will be to isolate certain devices to this router. This assumes you already have an internet connected router.

### Install
**Latest version when writing this:** 22.03.0
- Select your image from [here](https://openwrt.org/toh/raspberry_pi_foundation/raspberry_pi)
- We will be using the image for [Raspberry Pi 3 Model B](https://downloads.openwrt.org/releases/22.03.0/targets/bcm27xx/bcm2710/openwrt-22.03.0-bcm27xx-bcm2710-rpi-3-ext4-factory.img.gz)
- Flash an SD card using [balena etcher](https://www.balena.io/etcher/)
- Start the RPI with your new SD card loaded with OpenWRT

### Configure
