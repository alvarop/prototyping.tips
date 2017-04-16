# prototyping.tips

## Basics
* Breadboard
* Jumper wires
* Power supply
* Soldering iron

## Misc
* Microscope
* SMD Resistor/Capacitor books
* Heat shrink tubing
* Electrical tape

## Measuring things

### Multimeter

### [Saleae Logic](http://saleae.com)
* 4/8/16 channel logic analyzer (digital + analog)
* Tons of protocol analyzers (easy to create new ones)
* Constant stream of data (Limited only by RAM and USB speed)
* Awesome cross-platform UI/SDK

### [Analog Discovery 2](http://analogdiscovery.com/)
* "A portable USB laboratory"
* 2 channel oscilloscope and waveform generator
* 16 channel logic analyzer/pattern generator
* Variable power supply and voltmeter
* Spectrum/network analyzer
* Cross platform UI/SDK

### Oscilloscope

### [Beagle 480 USB protocol analyzer](http://www.totalphase.com/products/beagle-usb480/)
* Must have for HS/FS USB firmware projects
* Not cheap, but quickly pays for itself

## Talking to things

### USB-to-serial
#### [FTDI](http://www.ftdichip.com)
* Most common IC used. Great hardware, drivers not-so-much
* Beware of counterfit parts!

#### Other
* MCP2200
* CP210x

### [BusPirate](http://dangerousprototypes.com/docs/Bus_Pirate)
* USB to I2C/SPI/JTAG/UART/1wire/MIDI/etc..
* Serial terminal interface
* Lots of examples with python/c/perl/etc

### [GoodFET](http://goodfet.sourceforge.net/[GreatFET](http://greatscottgadgets.com/greatfet/)
* Open-source JTAG adapter turned general purpose USB-various peripheral interface
* GreatFET is HS USB version (in development) with many more capabilities

### [Silta](http://github.com/alvarop/silta)
* Firmware for STM32F4 Discovery board
* USB-to-(SPI/I2C/ADC/DAC/PWM/GPIO) bridge
* USB serial terminal interface or Python library
* Easy to test things without writing any firmware
* Built-in USB DFU bootloader for easy updates

### [Arduino](http://www.arduino.cc)
* Easy to use
* Tons of examples
* Great for quick prototypes

### [Teensy](http://pjrc.com/teensy)
* Faster/smaller than Arduino
* Arduino compatible
* Lots of great libraries with HW support

### Beaglebone

### RaspberryPi

## Programming Things

### [Black Magic Probe v2](http://1bitsquared.com/products/black-magic-probe)
* ARM JTAG/SWD debugger
* Exposes gdb server over USB
* No special software needed

### [BusBlaster](http://dangerousprototypes.com/docs/Bus_Blaster)
* Open source JTAG/SWD tool
* Works with openOCD and urJTAG

### ST-Link
* Included with most ST dev boards
* ARM SWD

### [Segger JLink](http://www.segger.com/jlink-debug-probes.html)
* Industry standard JTAG/SWD
* Not cheap, works great
* Affordable EDU version

## Making things
### EDA Tools
#### [Kicad](http://kicad-pcb.org)
#### [Eagle](http://www.autodesk.com/products/eagle/overview)

### PCB Manufacturing
#### [OSHPark](http://oshpark.com/)
* Cheap purple PCB’s, fast
* $5/square inch for 3 boards
* Offers 2 and 4 layers, discount for high volumes
* Super easy to use

#### [MacroFab](http://macrofab.com/)
* Full service PCB manufacturing/assembly
* Upload board files/BOM, get quote, confirm placement, order boards

#### [PCB:NG](http://pcb.ng/)
* Full service PCB manufacturing/assembly

#### [OSH Stencils](http://www.oshstencils.com)
* Like OSHPark, but for PCB stencils.
* Kapton and stainless steel
* Super fast to ship

### Mechanical CAD
#### [Onshape](http://www.onshape.com)
* Browser based
* Free for personal(public) use

#### [Autodesk Fusion 360](http://www.autodesk.com/products/fusion-360/overview)
* Windows/macOS support
* Subscription service, free for students

### Mechanical Manufacturing
#### [3D Hubs](http://www.3dhubs.com)
* Upload 3d file, get locally printed part!
* Uses 3d printers in your area
* Instant quote depending on technology/materials

#### [Parts Badger](http://parts-badger.com)
* On-demand machining
* Upload files for instant quote with various materials
