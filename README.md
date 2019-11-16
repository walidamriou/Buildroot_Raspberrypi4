# Buildroot Raspberrypi4
Using Buildroot for building Embedded Linux Systems on Raspberry Pi 4 Model B

##### Projects in this repository
1- Simple OS for Raspberry pi 4:


##### Specifications of Raspberry pi 4 model B
- Broadcom BCM2711, Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.5GHz
-1GB, 2GB or 4GB LPDDR4-3200 SDRAM (depending on model)
- 2.4 GHz and 5.0 GHz IEEE 802.11ac wireless, Bluetooth 5.0, BLE
- Gigabit Ethernet
- 2 USB 3.0 ports; 2 USB 2.0 ports.
- Raspberry Pi standard 40 pin GPIO header (fully backwards compatible with previous boards)
- 2 × micro-HDMI ports (up to 4kp60 supported)
- 2-lane MIPI DSI display port
- 2-lane MIPI CSI camera port
- 4-pole stereo audio and composite video port
- H.265 (4kp60 decode), H264 (1080p60 decode, 1080p30 encode)
- OpenGL ES 3.0 graphics
- Micro-SD card slot for loading operating system and data storage
- 5V DC via USB-C connector (minimum 3A*)
- 5V DC via GPIO header (minimum 3A*)
- Power over Ethernet (PoE) enabled (requires separate PoE HAT)
- Operating temperature: 0 – 50 degrees C ambient

* A good quality 2.5A power supply can be used if downstream USB peripherals consume less than 500mA in total.



#### Sources and documentations:
* About Raspberry pi 4 model B:  
https://www.raspberrypi.org/products/raspberry-pi-4-model-b/specifications/?variant=raspberry-pi-4-model-b-4gb

* raspberry pi console commands:   
https://www.raspberrypi.org/documentation/linux/usage/commands.md

* RaspberryPi defconfig files in Buildroot:   
https://github.com/buildroot/buildroot/tree/master/board/raspberrypi
