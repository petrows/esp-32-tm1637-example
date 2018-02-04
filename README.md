# esp32-tm1637 LCD library

## Introduction

This is an example of control TM1637 LCD 7-segment display using ESP-32 IDF toolchain [ESP-IDF](https://github.com/espressif/esp-idf).

Clone example + submodules:

    $ git clone --recursive https://github.com/petrows/esp-32-tm1637.git

Build the application with:

    $ cd esp32-tm1637-example
    $ make menuconfig    # Configure your GPIO pins for LCD connection
    $ make flash monitor
    
## Hardware

No special confugration needed, no pullup resistors needed. Just connect your LCD and configure example.

`make menuconfig` can be used to set the TM1637 GPIOs.

## Source Code

The source is available from [petrows/esp-32-tm1637-example](https://github.com/petrows/esp-32-tm1637-example).

## License

The code in this project is licensed under the MIT license - see LICENSE for details.
