The DigitalIn interface is used to read the value of a digital input pin.

Any of the numbered mbed pins can be used as a DigitalIn. 

## Hello World!

[![View code](https://www.mbed.com/embed/?url=https://developer.mbed.org/users/samux/code/USBMouseKeyboard_HelloWorld)](https://developer.mbed.org/users/samux/code/USBMouseKeyboard_HelloWorld/file/09cebc93f3a7/main.cpp>) [![View code](<https://www.mbed.com/embed/?type=program)](https://developer.mbed.org/users/mbed_official/code/DigitalIn_HelloWorld_FRDM-KL25Z/docs/tip/main_8cpp_source.html>)

## API

API summary

[![View code](<https://www.mbed.com/embed/?type=library)](https://developer.mbed.org/users/mbed_official/code/mbed/docs/tip/classmbed_1_1DigitalIn.html>)

## Interface

The DigitalIn Interface can be used on any pin with a blue label.

The pin input is logic '0' for any voltage on the pin below 0.8v, and '1' for any voltage above 2.0v. By default, the DigitalIn is setup with an internal pull-down resistor.

[![https://developer.mbed.org/media/uploads/chris/pinout-thumbnails.jpg](https://developer.mbed.org/media/uploads/chris/pinout-thumbnails.jpg)](/handbook/Pinouts)  
---  
[See the Pinout page for more details](/handbook/Pinouts)  
  
## Related

To handle an interrupt, see [InterruptIn](InterruptIn)

Examples of logical functions

```

  1. include "mbed.h"

DigitalIn a(p5); DigitalIn b(p6); DigitalOut z_not(LED1); DigitalOut z_and(LED2); DigitalOut z_or(LED3); DigitalOut z_xor(LED4);

int main() { while(1) { z_not = !a; z_and = a &amp;&amp; b; z_or = a || b; z_xor = a ^ b; } }

```
