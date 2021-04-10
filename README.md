# ANET A8 Ramps 1.4 Marlin 3D Printer Firmware

This Marlin's Configuration.h file is modified for Anet A8 with Ramps 1.4 Board (Arduino 2560) 

You need a Ramps 1.4 Board with Anet A8 (Or any other printer)
This configuration is Tested and used by Me.

1) You have to download these files (Or just configuration.h for another marlin 2.x folder) .

2) Extract it, in Marlin > Folder.

3) You can Edit Configuration.h file.

4) Run Linux (Ubuntu, in my case) (Because Marlin is NOT Compiling in Windows 10)

5) Download Arduino Latest (1.8.13) from arduino site. (Search for install instructions on internet) ( Run it by "Sudo Arduino" )

6) Install U8glib (Newest Version) by Arduino > Tools > Manage Libraries.

7) Select Arduino Mega 2560 from Arduino > Tools > Board

8) Select the /dev/ttyUSB0 Port.

9) Press Compile , if successful press Upload.

Troubleshoot:

The Endstops are configured to Inverted (Ground Connection to Min Endstop Pin will trigger)

If any servo is running backwards, flip its Pins from Ramps Board.

I have set the E-Steps Calibration as i calibrated on my Printer.
You can test it by printing 10x10 Box.

Please increase PLA Nozzle temprature 10-20 Degree if your bed is not sticking it.




## Original From Marlin:

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).
Please test this firmware and let us know if it misbehaves in any way. Volunteers are standing by!

## Marlin 2.0

Marlin 2.0 takes this popular RepRap firmware to the next level by adding support for much faster 32-bit and ARM-based boards while improving support for 8-bit AVR boards. Read about Marlin's decision to use a "Hardware Abstraction Layer" below.

Download earlier versions of Marlin on the [Releases page](https://github.com/MarlinFirmware/Marlin/releases).

## Building Marlin 2.0

To build Marlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [PlatformIO](http://docs.platformio.org/en/latest/ide.html#platformio-ide). Detailed build and install instructions are posted at:

  - [Installing Marlin (Arduino)](http://marlinfw.org/docs/basics/install_arduino.html)
  - [Installing Marlin (VSCode)](http://marlinfw.org/docs/basics/install_platformio_vscode.html).


