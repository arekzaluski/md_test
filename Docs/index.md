The USBHostMSD interface is used to access a USB mass storage device.

<div class="alert-box warning" title="Library in Beta!"> This library is in Beta. If you have any problems using the USBHost library, please send a bug report at [support@mbed.org](support@mbed.org) </div>

The USB Host connector should be attached to 

  * **p31 (D+), p32 (D-) and GND** for the **LPC1768**
  * add **two 15k resistors tied to GND on D+ and D-**i

## Hello World

[![View code](https://www.mbed.com/embed/?url=https://developer.mbed.org/users/samux/code/USBHostMSD_HelloWorld/)](https://developer.mbed.org/users/samux/code/USBHostMSD_HelloWorld/file/tip/main.cpp)

## API

[![View code](https://www.mbed.com/embed/?url=https://developer.mbed.org/users/mbed_official/code/USBHost/)](https://developer.mbed.org/users/mbed_official/code/USBHost/file/tip/main.cpp) 

<div class="alert-box warning" title="Troobleshooting"> If your mbed board is automatically resetted when you plug a USB device, you should consider to use an external power supply </div>

## Related

  * [USBHostMouse](USBHostMouse)
  * [USBHostKeyboard](USBHostKeyboard)
  * [USBHostSerial](USBHostSerial)
  * [USBHostHub](USBHostHub)
