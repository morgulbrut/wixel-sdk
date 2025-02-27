Pololu Wixel Software Development Kit (SDK)

This package contains code and Makefiles that will help you create
your own applications for the Pololu Wixel.  The Wixel is a general-
purpose programmable module featuring a 2.4 GHz radio and USB.  The
Wixel is based on the CC2511F32 microcontroller from Texas Instruments,
which has an integrated radio transceiver, 32 KB of flash memory, 4 KB
of RAM, and a full-speed USB interface.

For documentation of this SDK, see:
http://pololu.github.com/wixel-sdk

(You can also generate the documentation yourself by running
Doxygen on libraries/Doxyfile.)

For more information about the Wixel, see the Wixel User's Guide:
http://www.pololu.com/docs/0J46


## Installation on linux
1. clone this repo 
2. get the wixelcmd and wixelconfig tools from https://www.pololu.com/product/1336/resources (Wixel Software archive)
3. copy/move wixelcmd and wixelconfig into the root of your local copy of this repo
4. install the sdcc compiler (for archlinux  `pacman -S sdcc`)
