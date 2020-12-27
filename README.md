# OpenCore drivers and configuration file for ASUS UX431F

This repo only contains the assembled SSDTs, Kernel Extensions needed and the Configuration file. It's not finished but I decided to share it to the world.

Tested in macOS 10.15.x and 11.0.1, currently running Big Sur in my machine (remember to change AirportItlwm if you're using Catalina!)

## What works
Almost everything. It's easier to list...

## What doesn't work

* Webcam - although you can use a Virtual Machine (VMware Fusion with Windows or QEMU with Linux) and doing a passthrough of the Device and Vendor ID of the Webcam USB in order to get it, I would like to make it just working...
* Fingerprint sensor - and it would never do, only Windows.

## Untested
* SD card reader - probably won't work.

## What needs work
* Keyboard backlight - it remains on if booting from another OS.
* FN keys - maybe it will help with the other

Any help would be appreciated!

# Changelog

## December 7th 2020

Trackpad now works :-)
