# pispot
A Raspberry Pi hotspot router for use as a travel router

## Requirements
Here is what you need to build the pispot travel router.
* Raspberry pi (2 or 3)
* Wifi dongle (2 if using a raspberry pi 2)

## Features
* VNC Server for configuring wifi over hotel click-through page
* Bind9, including scripts to block ads
* DHCP
* Wifi Hotspot

## Setup
Download the latest Raspbian Jesse image and istall it in the usual way.
* Update the raspbian image with apt-get update and apt-get upgrade, reboot
* In raspi-config, expand the filesystem to use the full size
* Install tightvncserver with sudo apt-get install tightvncserver
