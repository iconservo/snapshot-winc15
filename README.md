# WINC1500 WiFi driver for mbed-os

The mbed OS driver for the [Microchip WINC1500 WiFi module](https://www.microchip.com/wwwproducts/en/ATwinc1500)

Example Arduino form factor carrier board: https://www.adafruit.com/product/3653

Winc1500 implements full IP networking stack on the module, including TLS, and exposes a socket-like RPC API over serial bus ( currently only SPI supported ). The serial bus wrapper is provided by [Atmel ASF](http://asf.atmel.com/docs/latest/)

![Winc1500](https://cdn-shop.adafruit.com/970x728/3653-00.jpg)

Note: WINC1500 has a more full featured cousin [WINC3400](https://www.microchip.com/wwwproducts/en/ATWINC3400) which integrates BLE on the same module
