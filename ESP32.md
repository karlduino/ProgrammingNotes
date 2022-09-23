## ESP32 board

Purchased [this board](https://amzn.to/3RcA2H4) from amazon Says "ESP-WROOM-32" on the
chip. I selected ESP32 Arduino -> ESP-WROOM-DA module

Got it to blink an LED; use an integer (like 4) for a GPIO pin.

Able to attach an I2C LCD display.
Connected GND->GND, VCC->VIN, SDA->D21, SCL->D22
Worked with the LCD_I2C library
