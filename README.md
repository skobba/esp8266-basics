# ESP8266 Basics

# Serial drivers for Mac
"It's not a esp8266 driver, it's a driver for the USB-Serial IC on the board. different vendors use different ICs, so you need to identify which yours has and find a driver for it."

## Naming
In platformio: upload_port = /dev/cu.SLAB_USBtoUAR


## Siliabs
https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
* /dev/cu.SLAB_USBtoUART

## http://wch.cn
http://wch.cn/download/CH341SER_ZIP.html
* /dev/cu.usbserial-1430
* /dev/cu.wchusbserial1430 (Tested on Mojave)

