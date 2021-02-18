
### The following software is all personally authored and [free for public use](LICENSE) unless noted otherwise.

### PGP/SSH public keys are located at [ardnew.com/keys](https://ardnew.com/keys). Backups are stored on GitHub at [ardnew/keys](keys).

#### Pull requests, criticism, and [donations](https://cash.app/$ardnew) welcome. *No refunds*.

###### Each repository is assigned a subjective color code (㏄) to indicate its status and general quality. See [Color Code](#color-code) for definitions.

# [Go](https://golang.org/) 

#### Modules

[mcp2221adocimg]:https://godoc.org/github.com/ardnew/mcp2221a?status.svg
[mcp2221adocurl]:https://godoc.org/github.com/ardnew/mcp2221a
[ft232hdocimg]:https://godoc.org/github.com/ardnew/ft232h?status.svg
[ft232hdocurl]:https://godoc.org/github.com/ardnew/ft232h

[versiondocimg]:https://godoc.org/github.com/ardnew/version?status.svg
[versiondocurl]:https://godoc.org/github.com/ardnew/version

[ipseqdocimg]:https://godoc.org/github.com/ardnew/ipseq?status.svg
[ipseqdocurl]:https://godoc.org/github.com/ardnew/ipseq

|[㏄](#color-code)|Repository|Documentation|Description|
|-----------------|:--------:|:-----:|:----------|
|[🟦](#color-code)|[`ardnew/mcp2221a`](https://github.com/ardnew/mcp2221a)|[![GoDoc][mcp2221adocimg]][mcp2221adocurl]|Go module for the MCP2221A USB to I²C/UART Protocol Converter with GPIO|
|[🟦](#color-code)|[`ardnew/ft232h`](https://github.com/ardnew/ft232h)|[![GoDoc][ft232hdocimg]][ft232hdocurl]|Go module for FTDI FT232H USB to GPIO/SPI/I²C/JTAG/UART protocol converter|
|[🟩](#color-code)|[`ardnew/version`](https://github.com/ardnew/version)|[![GoDoc][versiondocimg]][versiondocurl]|Go module to easily embed semantic versioning compliance with change history|
|[🟦](#color-code)|[`ardnew/ipseq`](https://github.com/ardnew/ipseq)|[![GoDoc][ipseqdocimg]][ipseqdocurl]|Go module to parse and iterate over IPv4 address intervals|
|[🟨](#color-code)|[`ardnew/oibot`](https://github.com/ardnew/oibot)|--|Go package for controlling iRobot Create 2 robots using Open Interface (OI) specification|

#### Shell integration

|[㏄](#color-code)|Repository|Command|Target/Host|Description|
|-----------------|:--------:|:-----:|:---------:|:----------|
|[🟦](#color-code)|[`ardnew/gosh`](https://github.com/ardnew/gosh)|[`cmd/gosh`](https://github.com/ardnew/gosh/tree/master/cmd/gosh)|Linux|Launch shell with YAML-driven environment|
|[🟦](#color-code)|[`ardnew/gosh`](https://github.com/ardnew/gosh)|[`cmd/goshfun`](https://github.com/ardnew/gosh/tree/master/cmd/goshfun)|Linux|Generate command-line interface for Go library functions|

#### Utility

[rosterdocimg]:https://godoc.org/github.com/ardnew/roster?status.svg
[rosterdocurl]:https://godoc.org/github.com/ardnew/roster
[mkgodocimg]:https://godoc.org/github.com/ardnew/mkgo?status.svg
[mkgodocurl]:https://godoc.org/github.com/ardnew/mkgo
[wslpathdocimg]:https://godoc.org/github.com/ardnew/wslpath?status.svg
[wslpathdocurl]:https://godoc.org/github.com/ardnew/wslpath

|[㏄](#color-code)|Repository|Command|Documentation|Description|
|-----------------|:--------:|:-----:|:-----------:|:----------|
|[🟦](#color-code)|[`ardnew/roster`](https://github.com/ardnew/roster)|`roster`|[![GoDoc][rosterdocimg]][rosterdocurl]|Check which files have changed using configurable directory index file|
|[🟦](#color-code)|[`ardnew/ipseq`](https://github.com/ardnew/ipseq)|[`cmd/ipseq`](https://github.com/ardnew/ipseq/tree/master/cmd/ipseq)|[![GoDoc][ipseqdocimg]][ipseqdocurl]|Print IPv4 addresses in ranges similar to `seq` from [GNU coreutils](https://github.com/coreutils/coreutils)|
|[🟩](#color-code)|[`ardnew/lcpre`](https://github.com/ardnew/lcpre)|`lcpre`|--|Determine the longest common prefix among multiple strings|
|[🟦](#color-code)|[`ardnew/mkgo`](https://github.com/ardnew/mkgo)|`mkgo`|[![GoDoc][mkgodocimg]][mkgodocurl]|Create a Go main module using template source file|
|[🟦](#color-code)|[`ardnew/wslpath`](https://github.com/ardnew/wslpath)|`wslpath`|[![GoDoc][wslpathdocimg]][wslpathdocurl]|Convert between Windows and Linux file paths in WSL|

#### [Raspberry Pi](https://www.raspberrypi.org/)

|[㏄](#color-code)|Repository|Command|Target/Host|Description|
|-----------------|:--------:|:-----:|:---------:|:----------|
|[🟩](#color-code)|[`ardnew/rpireboot`](https://github.com/ardnew/rpireboot)|`rpireboot`|Linux (systemd)|Raspberry Pi service to reboot system on GPIO interrupt|
|[🟨](#color-code)|[`ardnew/remax`](https://github.com/ardnew/remax)|`remax`|Linux|Maximize serial terminal based on current window size|

# [TinyGo](https://tinygo.org/)

#### [Microcontrollers](https://tinygo.org/microcontrollers/) (board support)

|[㏄](#color-code)|Repository|Branch|Target/Host|Hardware Support|
|-----------------|:--------:|:----:|:---------:|:-----:|
|[🟦](#color-code)|[`ardnew/tinygo`](https://github.com/ardnew/tinygo)|[board/teensy40](https://github.com/ardnew/tinygo/tree/board/teensy40)|[PJRC Teensy 4.0](https://www.pjrc.com/store/teensy40.html)|GPIO, NVIC, ADC, UART, I²C, SPI|
|[🟦](#color-code)|[`ardnew/tinygo`](https://github.com/ardnew/tinygo)|[board/matrixportal-m4](https://github.com/ardnew/tinygo/tree/board/matrixportal-m4)|[Adafruit Matrix Portal M4](https://learn.adafruit.com/adafruit-matrixportal-m4)|GPIO, NVIC, ADC, PWM, UART, I²C, SPI, HUB75|
|[🟦](#color-code)|[`ardnew/tinygo`](https://github.com/ardnew/tinygo)|[board/feather-stm32f405](https://github.com/ardnew/tinygo/tree/board/feather-stm32f405)|[Adafruit STM32F405 Feather](https://learn.adafruit.com/adafruit-stm32f405-feather-express)|GPIO, UART, I²C, SPI|

#### [`import "tinygo.org/x/drivers"`](https://github.com/tinygo-org/drivers/) (peripheral drivers)
|[㏄](#color-code)|Repository|Branch|Target/Host|Interface|Description|
|-----------------|:--------:|:----:|:---------:|:-------:|:----------|
|[🟦](#color-code)|[`ardnew/tinygo-stusb4500`](https://github.com/ardnew/tinygo-stusb4500)|[`stusb4500`](https://github.com/ardnew/drivers/tree/stusb4500)|\*|I²C|[STUSB4500](https://www.st.com/resource/en/datasheet/stusb4500.pdf) USB PD sink controller|
|[🟦](#color-code)|[`ardnew/drivers`](https://github.com/ardnew/drivers)|[`rgb75`](https://github.com/ardnew/drivers/tree/rgb75)|ATSAMD51|GPIO|HUB75 RGB LED matrix panel|
|[🟦](#color-code)|[`ardnew/drivers`](https://github.com/ardnew/drivers)|[`stm32f4-spi`](https://github.com/ardnew/drivers/tree/stm32f4-spi)|STM32F4|SPI|ILI9341 TFT LCD (Adafruit STM32F405 Feather)|
|[🟦](#color-code)|[`ardnew/drivers`](https://github.com/ardnew/drivers)|[`teensy40-spi`](https://github.com/ardnew/drivers/tree/teensy40-spi)|MIMXRT1062|SPI|ILI9341 TFT LCD (Teensy 4.0/4.1)|

# [Arduino](https://www.arduino.cc/)

|[㏄](#color-code)|Repository|Target/Host|Description|
|-----------------|:--------:|:---------:|:----------|
|[🟦](#color-code)|[`ardnew/STUSB4500`](https://github.com/ardnew/STUSB4500)|Arduino|Arduino library for real-time capabilities of the STUSB4500 USB PD sink controller|
|[🟩](#color-code)|[`ardnew/timecard`](https://github.com/ardnew/timecard)|Arduino|PyPortal (Arduino) application to track hours charged to projects|
|[🟩](#color-code)|[`ardnew/ILI9341-Layout-Manager`](https://github.com/ardnew/ILI9341-Layout-Manager)|Arduino|An autolayout engine with callback support for designing and organizing buttons, text fields, and modal windows for ILI9341 chipsets|
|[🟩](#color-code)|[`ardnew/XPT2046_Calibrated`](https://github.com/ardnew/XPT2046_Calibrated)|Arduino|XPT2046_Touchscreen library (Paul Stoffregen) fork with added 3-point calibration|
|[🟩](#color-code)|[`ardnew/StatusLED`](https://github.com/ardnew/StatusLED)|Arduino|Single-LED RGB driver for Arduino, intended for use with onboard Neopixel/DotStar/RGB LEDs|
|[🟨](#color-code)|[`ardnew/upd-layman`](https://github.com/ardnew/upd-layman)|Arduino|USB-C Power Delivery protocol analyzer and sink controller with versatile touchscreen interface|
|[🟨](#color-code)|[`ardnew/pwsens-8266`](https://github.com/ardnew/pwsens-8266)|Arduino|Voltage and current monitor with Adafruit INA260 for the Heltec WiFi Kit 8 OLED|

# [STM32](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html)

|[㏄](#color-code)|Repository|Target/Host|Description|
|-----------------|:--------:|:---------:|:----------|
|[🟦](#color-code)|[`ardnew/ILI9341-STM32-HAL`](https://github.com/ardnew/ILI9341-STM32-HAL)|STM32|ILI9341 color TFT display and XPT2046 touchscreen driver for STM32 using HAL SPI with DMA|
|[🟦](#color-code)|[`ardnew/INA260-STM32-HAL`](https://github.com/ardnew/INA260-STM32-HAL)|STM32|INA260 voltage/current sensor driver for STM32 using HAL I²C|

# [Perl 5](https://www.perl.org/)

|[㏄](#color-code)|Repository|Command|Target/Host|Description|
|-----------------|:--------:|:-----:|:---------:|:----------|
|[🟧](#color-code)|[`ardnew/perl-mod`](https://github.com/ardnew/perl-mod)|--|\*|Pure Perl modules for I/O, functional iterators, files, and list utilities.|
|[🟩](#color-code)|[`ardnew/pcp`](https://github.com/ardnew/pcp)|`pcp`|\*|File and directory copy on ~~steroids~~PCP|
|[⬛](#color-code)|[`ardnew/ios-scripts`](https://github.com/ardnew/ios-scripts)|`iosctrl`|macOS|Analyze, compile, and package iOS applications from Xcode projects|
|[🟩](#color-code)|[`ardnew/bases`](https://github.com/ardnew/bases)|`bases`|\*|Evaluate and print expressions in various bases|
|[🟩](#color-code)|[`ardnew/chars`](https://github.com/ardnew/chars)|`chars`|\*|Print ASCII and regular expression character class tables|

# [Bash](https://www.gnu.org/software/bash/)

|[㏄](#color-code)|Repository|Command|Target/Host|Description|
|-----------------|:--------:|:-----:|:---------:|:----------|
|[🟩](#color-code)|[`ardnew/bash-arduino`](https://github.com/ardnew/bash-arduino)|`ino`|\*|bash environment and utilities for simplifying `arduino-cli` interactions|

# [Delphi](https://www.embarcadero.com/products/delphi/)

|[㏄](#color-code)|Repository|Command|Target/Host|Description|
|-----------------|:--------:|:-----:|:---------:|:----------|
|[🟧](#color-code)|[`ardnew/mswin-systool`](https://github.com/ardnew/mswin-systool)|`SysTool.exe`|Windows XP/7|System tray utility for bit pattern manipulation (two's-complement, IEEE-754, base conversions), file analysis (hex dump, checksum, NTFS/FAT attributes), and other stuff.|

# Projects

## Wireless LED Strip Controllers/Drivers

Two separate projects for implementing a wirelessly-controlled LED strip using Bluetooth Low-Energy (LE):

### **Blixel** — General-purpose wireless LED strip controller for Android mobile phones/tablets
#####   Android mobile device -_to_- Arduino-driven LED strip

|[㏄](#color-code)|Repository|Application|Target/Host|
|-----------------|:--------:|:---------:|:---------:|
|[🟩](#color-code)|[`ardnew/ItsyBitsy-BLE-LED`](https://github.com/ardnew/ItsyBitsy-BLE-LED)|`ItsyBitsy-BLE-LED`|Adafruit ItsyBitsy nRF52840 (Arduino/C++)|
|[🟩](#color-code)|[`ardnew/Android-BLE-LED`](https://github.com/ardnew/Android-BLE-LED)|`Blixel`|Android (Java)|

Designed for Android mobile devices, implemented using an Adafruit ItsyBitsy nRF52840 and a 300-pixel (5 meters) RGB LED WS2815 strip. 

Instead of the commonly-found Bluetooth (LE) to serial UART string-based frameworks (_**hacks!**_), a custom BLE GATT protocol was designed as communication transport — which provides a rich, structured message framework for **much faster** (and more reliable) communication to transmit per-pixel and/or per-segment color information.

Currently supports several modes of operation: 

- Color fill entire strip, partial strip (segment), or individual pixels
- Parameterized animation patterns (color wheel, theater chase, and fade/breathe)
- Optional motion-activated trigger (passive-infrared or doppler radar) with timer — great as a nightlight!

### **NeoCLUE** — Real-time sensor-reactive wireless LED strip controller
#####   Arduino sensor-based device -_to_- Arduino-driven LED strip

|[㏄](#color-code)|Repository|Application|Target/Host|
|-----------------|:--------:|:---------:|:---------:|
|[🟩](#color-code)|[`ardnew/NeoCLUE`](https://github.com/ardnew/NeoCLUE)|[`Controller`](https://github.com/ardnew/NeoCLUE/tree/master/sketchbook/Controller)|Adafruit CLUE nRF52840 (Arduino/C++)|
|[🟩](#color-code)|[`ardnew/NeoCLUE`](https://github.com/ardnew/NeoCLUE)|[`Driver`](https://github.com/ardnew/NeoCLUE/tree/master/sketchbook/Driver)|Adafruit ItsyBitsy nRF52840 (Arduino/C++)|

Similar to the Android-based project above, but implemented using a pair of Arduino-based Nordic nRF52840 devices. 

Additionally, this project is designed to utilize the suite of environmental sensors embedded on the Controller (Adafruit CLUE). 

For example, the user can control the LED strip color in real-time using the accelerometer (e.g., X, Y, and Z-axis mapped to the Red, Green, and Blue components, respectively, of the RGB-colored LEDs), gyroscope, magnetometer, air temperature, barometric pressure, humidity, light color, proximity, gesture sensor, or PDM microphone. 

Various animation patterns (e.g., color pulse/fade using microphone audio levels, rainbow pattern with origin seeded by magnetic North, etc.) are also supported.

The onboard IPS LCD screen provides a rich GUI interface based on the LVGL embedded graphics library.

## WiFi-Enabled Timecard 

|[㏄](#color-code)|Repository|Target/Host|
|-----------------|:--------:|:---------:|
|[🟩](#color-code)|[`ardnew/timecard`](https://github.com/ardnew/timecard)|Adafruit PyPortal (SAMD51) (Arduino/C++)|

This software lets you select a project and an associated activity, then you can start and stop a timer that tracks how many hours you worked on that activity.

Designed for the Adafruit PyPortal, it takes advantage of the ESP32 WiFi module by automatically synchronizing local time with an NTP server. Additionally, time is tracked by logging to the internal SD card, making it easy to open and read from a PC when you actually submit your hours wherever. Alternatively, if your time-tracking system and the PyPortal are on a shared network, the software could easily be modified to submit your time automatically.

# Color Code

|Color|Status|Description|Active|
|-----|:----:|:----------|:----:|
|🟦|**Excellent**|Robust, tested, stable, well-documented|✓|
|🟩|**Good**|Correct, easy to use or understand|✓|
|🟨|**Reusable**|Functional, may require modification|✓|
|🟧|**Deprecated**|No longer used or maintained| |
|🟥|**Broken**|Partially implemented, missing or broken capabilities|✓|
|⬛|**⁉**|Y̴o̵u̶ ̷m̵̦̚à̷̤y̶̧̕ ̸̱͋ḧ̵̰̻́̐̉̚a̸͕̰̅̍͊̓͆v̷͚̳̏̿̓͊é̶̡̯̘̻͈̐̌̎̾ ̴̖͔̯̪̠̾̎s̴̲̣̮͒̏̿͝ȩ̴̦͎̥̻̰͇͆̾ŗ̴̪̰̥̽̑́͒̈́i̶̢͕̺̲͕̬͊̀̓ô̵̹̲͉̼̻̎̽u̶̡̢̢̫̳͔̓͑̂̔̑̃͘s̴͕̊͆̅̕ ̵̘͓͙̃͘p̵̺̠̥̝͔̀ṙ̶̡̺̣̞̯̆̏͜ő̸̧b̵̫̜͖̓̈͒͗ĺ̴̢̝͖̬͙̳̀ę̸̹͒̐̓̌̿̽͝ͅm̸̟̬̪̣̖̮͒̍͊̐͑͛͘s̷̛̫̤͐͗̇̾̃ ̸̢̛̣͋̐̎͋̎̈́u̶̳̥̭͑́̓̀͌̆s̶̥̭̝̯̃͊̕͘͠͠į̷̛̳̤͈̬̍͗̅̀ń̶̦͊̌̔̑͗͗g̷͎͐́̑ ̶̘͓̺̱͆̓͜ţ̶̢̡̧͉̜͙͙͚̘͓̼̝͙̥͔̟̦͓̮̯̞̘̞̫̺̱̖̀̉ḩ̶̨̧̡̛͈͍̙̖̮̫͚̜̜̮̦̻̼͉̪̻̹̀̌͊̽̓̄́̓̿̋͌̑͌͐̒͌͑̋̕̕̚ȋ̴̧̛̼̘̼̙̟͍̥̱͌̍͂́̐͐̈́̆̍̀͑̀̑͒͘s̶̮̖̟͔̥̮̭̥̺͕̲̪̪̅̑͜͝͝ ̸̝̹͕̬̱̠́̽̍̒͛͆͛̔͌̔̊̓̂̈̄̿͑̆͆̈́͑̂̐͘͝s̴̨̞͉̼̮̱̠̤̤̦͍͇̹̗̯̖̱͓͈̭̩̞̄͐͂͒͛̓̌̍̈́̐͛̏̐̀̀̕̚͘͘͘̕͜͜͝ǫ̷̢̡̢̡̛̟̙̥͚̬̹̼̺̦̭͇͈̣̥̝̂̌̊̓̿̃́̔̃̐̅̕̕f̶̟̳̮̠͔̻̾́̌͛̉͜ͅţ̶̢̡̧͉̜͙͙͚̘͓̼̝͙̥͔̟̦͓̮̯̞̘̞̫̺̱̖̀̉w̶̢̲̘̙̭̭̣̫̬͎̖͔͚̗̟̣̠͓̘̮͓̞͎̪̲͓̖̝̦̘͉̋̌͐͛̈̃̃͊͐͘͝͠ą̷̛̛̛̖̭͉̦̗̱̠̜͈͚͖̰̟͓̇͒̂̐̀̏̑͛̎̈̈̆̌͑̓̌͐̅̓͊̀̌̊̅̈́̚̚̚͠r̸̢̨̡̨̨͎̯͙̩͖͖̦̪͖̠̺̜̳̘̞̠̪̭̙̭͍̝͓͕͎̩̯͈͖̮͂͛̇͐̎̌̃̄̀͜͝ͅę̷͍̫̟͉̮̼͗̊̌͂̆̐̄̊̈́̍̍̄̇͘͠͠| |

# Misleading Statistics

![ardnew's github stats](https://github-readme-stats.vercel.app/api?username=ardnew&show_icons=true&count_private=true&include_all_commits=true&custom_title=ardnew&theme=default)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ardnew&langs_count=8&theme=default)
