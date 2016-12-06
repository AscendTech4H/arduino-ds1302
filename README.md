# DS1302 RTC library for Arduino

This project is a library for the [Arduino](http://arduino.cc) platform. It
provides a simple interface to the
[Maxim DS1302](http://www.maximintegrated.com/en/products/digital/real-time-clocks/DS1302.html)
timekeeping chip. It allows Arduino projects to keep accurate time easily.

## Features

Of the features on the DS1302, this library provides support for:

* Setting and retrieving the time, using the burst modes.
* Setting and clearing the Write Protect (WP) flag.
* Setting and clearing the Clock Halt (CH) flag.
* Setting and accessing the 31 bytes of static RAM. Single-byte and multi-byte
  (burst) modes are supported.
* Low-level register access.

Trickle charging support is the only major feature of the DS1302 not directly
supported by this library. However, trickle charging can be enabled using the
low-level register access functions if desired.

## Examples and documentation

The [header file](DS1302.h) is well-commented, and the [examples](examples)
directory contains example sketches for immediate use.

## Installing

Download the zip of this repository. In Arduino, click Sketch -> Import Library -> Add .ZIP Library (formerly Add Library)
