# Go 

#### Modules

[mcp2221adocimg]:https://godoc.org/github.com/ardnew/mcp2221a?status.svg
[mcp2221adocurl]:https://godoc.org/github.com/ardnew/mcp2221a
[ft232hdocimg]:https://godoc.org/github.com/ardnew/ft232h?status.svg
[ft232hdocurl]:https://godoc.org/github.com/ardnew/ft232h

[versiondocimg]:https://godoc.org/github.com/ardnew/version?status.svg
[versiondocurl]:https://godoc.org/github.com/ardnew/version

[ipseqdocimg]:https://godoc.org/github.com/ardnew/ipseq?status.svg
[ipseqdocurl]:https://godoc.org/github.com/ardnew/ipseq

|Repository|Documentation|Description|
|:--------:|:-----:|:----------|
|[`ardnew/mcp2221a`](https://github.com/ardnew/mcp2221a)|[![GoDoc][mcp2221adocimg]][mcp2221adocurl]|Go module for the MCP2221A USB to I²C/UART Protocol Converter with GPIO|
|[`ardnew/ft232h`](https://github.com/ardnew/ft232h)|[![GoDoc][ft232hdocimg]][ft232hdocurl]|Go module for FTDI FT232H USB to GPIO/SPI/I²C/JTAG/UART protocol converter|
|[`ardnew/version`](https://github.com/ardnew/version)|[![GoDoc][versiondocimg]][versiondocurl]|Go module to easily embed semantic versioning compliance with change history|
|[`ardnew/ipseq`](https://github.com/ardnew/ipseq)|[![GoDoc][ipseqdocimg]][ipseqdocurl]|Go module to parse and iterate over IPv4 address intervals|
|[`ardnew/oibot`](https://github.com/ardnew/oibot)|--|Go package for controlling iRobot Create 2 robots using Open Interface (OI) specification|

#### Shell integration

|Repository|Command|Target/Host|Description|
|:--------:|:-----:|:---------:|:----------|
|[`ardnew/gosh`](https://github.com/ardnew/gosh)|[`cmd/gosh`](https://github.com/ardnew/gosh/tree/master/cmd/gosh)|Linux|Launch shell with YAML-driven environment|
|[`ardnew/gosh`](https://github.com/ardnew/gosh)|[`cmd/goshfun`](https://github.com/ardnew/gosh/tree/master/cmd/goshfun)|Linux|Generate command-line interface for Go library functions|

#### Raspberry Pi

|Repository|Command|Target/Host|Description|
|:---------|:-----:|:---------:|:----------|
|[`ardnew/rpireboot`](https://github.com/ardnew/rpireboot)|`rpireboot`|Linux (systemd)|Raspberry Pi service to reboot system on GPIO interrupt|
|[`ardnew/remax`](https://github.com/ardnew/remax)|`remax`|Linux|Maximize serial terminal based on current window size|

# Arduino

|Repository|Target/Host|Description|
|:---------|:---------:|:----------|
|[`ardnew/STUSB4500`](https://github.com/ardnew/STUSB4500)|Arduino|Arduino library for real-time capabilities of the STUSB4500 USB PD sink controller|
|[`ardnew/timecard`](https://github.com/ardnew/timecard)|Arduino|PyPortal (Arduino) application to track hours charged to projects|
|[`ardnew/ILI9341-Layout-Manager`](https://github.com/ardnew/ILI9341-Layout-Manager)|Arduino|An autolayout engine with callback support for designing and organizing buttons, text fields, and modal windows for ILI9341 chipsets|
|[`ardnew/XPT2046_Calibrated`](https://github.com/ardnew/XPT2046_Calibrated)|Arduino|XPT2046_Touchscreen library (Paul Stoffregen) fork with added 3-point calibration|
|[`ardnew/StatusLED`](https://github.com/ardnew/StatusLED)|Arduino|Single-LED RGB driver for Arduino, intended for use with onboard Neopixel/DotStar/RGB LEDs|
|[`ardnew/upd-layman`](https://github.com/ardnew/upd-layman)|Arduino|USB-C Power Delivery protocol analyzer and sink controller with versatile touchscreen interface|
|[`ardnew/pwsens-8266`](https://github.com/ardnew/pwsens-8266)|Arduino|Voltage and current monitor with Adafruit INA260 for the Heltec WiFi Kit 8 OLED|

# STM32

|Repository|Target/Host|Description|
|:---------|:---------:|:----------|
|[`ardnew/ILI9341-STM32-HAL`](https://github.com/ardnew/ILI9341-STM32-HAL)|STM32|ILI9341 color TFT display and XPT2046 touchscreen driver for STM32 using HAL SPI with DMA|
|[`ardnew/INA260-STM32-HAL`](https://github.com/ardnew/INA260-STM32-HAL)|STM32|INA260 voltage/current sensor driver for STM32 using HAL I²C|

# Perl

|Repository|Command|Target/Host|Description|
|:---------|:-----:|:---------:|:----------|
|[`ardnew/perl-mod`](https://github.com/ardnew/perl-mod)|--|\*|Pure Perl modules for I/O, functional iterators, files, and list utilities|
|[`ardnew/pcp`](https://github.com/ardnew/pcp)|`pcp`|\*|File and directory copy on ~~steroids~~PCP|
|[`ardnew/ios-scripts`](https://github.com/ardnew/ios-scripts)|`iosctrl`|macOS|Analyze, compile, and package iOS applications from Xcode projects|

# Bash

|Repository|Command|Target/Host|Description|
|:---------|:-----:|:---------:|:----------|
|[`ardnew/bash-arduino`](https://github.com/ardnew/bash-arduino)|`ino`|\*|bash environment and utilities for simplifying `arduino-cli` interactions|

# Delphi

|Repository|Command|Target/Host|Description|
|:---------|:-----:|:---------:|:----------|
|[`ardnew/mswin-systool`](https://github.com/ardnew/mswin-systool)|`SysTool.exe`|Windows XP/7/8/10|System tray utility for bit pattern manipulation (two's-complement, IEEE-754, base conversions), file analysis (hex dump, checksum, NTFS/FAT attributes), and other stuff|

# Projects

## Bluetooth Low-Energy (BLE) LED Strip Controller

|Repository|Application|Target/Host|
|:---------|:---------:|:---------:|
|[`ardnew/ItsyBitsy-BLE-LED`](https://github.com/ardnew/ItsyBitsy-BLE-LED)|`ItsyBitsy-BLE-LED`|Adafruit ItsyBitsy nRF52840 (Arduino/C++)|
|[`ardnew/Android-BLE-LED`](https://github.com/ardnew/Android-BLE-LED)|`Blixel`|Android (Java)|

Designed for Android mobile devices, implemented using an Adafruit ItsyBitsy nRF52840 and a 300-pixel (5 meters) RGB LED WS2815 strip. 

Instead of the commonly-found serial UART string protocols (hacks!), a custom BLE GATT protocol was designed as communication transport — which provides a structured message framework for **much** faster communication processing. 

Currently supports several modes of operation: 

- Color fill entire strip, subrange, or individual pixels
- Parameterized animation patterns (color wheel, theater chase, and fade/breathe)
- Optional motion-activated trigger (passive-infrared or doppler radar) with timer — great as a nightlight!

