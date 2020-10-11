# audiogene-avr

An interactive audio generator that evolves the sound based on interactions.

This provides the code for an Atmel microcontroller connected to multiple interactive inputs. It provides the input signals to control the genetic alrorithm.

## Build

The following dependencies need to be installed:

`sudo apt-get install gcc-avr binutils-avr avr-libc avrdude cmake`

`mkdir _build && cd _build`

`cmake ..`

`make`

## Flashing

Ensure power is applied to board, and connect AVR programmer to ICSP pins. Then run:

`make flash`

