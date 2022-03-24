# The ESP210 ESP8266 modile
![ESP210](https://ilabs.se/wp-content/uploads/2021/07/iso-front-1.png)

## ESP210 information
The ESP210 is a micro controller board packed with loads of functionality in a very small format for your projects that requires a WiFi connection.

The main controller of this board is the ESP8266 from Espressif connected to 4MByte of FLASH memory and with a total of 80KByte of internal SRAM. The ESP8266 MCU is built around the Tensilica Diamond Standard 106Micro's running at up to 160 MHz. It has a few basic digital peripherals and interfaces such as high speed SPI, I2C and a timer.

## ESP210 Key features
- Tensilica Diamond Standard 106Micro running at up to 160MHz
- 4 MB Flash, 80 KB RAM
- 2.4GHz WiFi modem
- UART, SPI, I2C
- PWM
- 10 - bit ADC
- USB 2.0

## The board

### WiFi solution
The WiFi radio is integrated onto the ESP8266 and you can read more about this at Espressifs website.

### Power
There is an onboard LDO that runs the onboard electronic devices.

### Other stuff
The ESP8266 does not have USB natively so on board there is a USB to serial bridge chip from Silabs called CP2104. This chip handles all the communication towards the PC. It also makes sure the ESP8266 is reset and that the boot mode pin is set correctly when you need to upload new firmware to the board.

### Pinout
<img src="https://ilabs.se/wp-content/uploads/2022/03/esp210-pinout-1-936x1024.png" alt="drawing"/>

### Software support
The board is supported by both the Arduino environment as well as PlatforIO.

## License
This design covered by the CERN Open Hardware Licence v1.2 and a copy of this license is also available in this repo.

## iLabs
<img src="https://ilabs.se/wp-content/uploads/2021/07/cropped-Color-logo-no-background.png" alt="drawing" width="200"/>

### About us
Invector Labs is a small Swedish engineering company that designs and build electronic devices for hobbyists as well as small and medium sized businesses.

For more information about this board you can visit the product page at our [website](https://ilabs.se/product/esp8266-module/)

Questions about this product can be addressed to <oshwa@ilabs.se>.

/* EOF */

