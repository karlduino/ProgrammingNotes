## Arduino Nano 33 IoT

- Need to get Arduino SAMD Core in Arduino IDE:

  - Tools -> Boards -> Boards Manager -> search for "SAMD" and install

- What is a 5V pin on the Nano and Nano Every doesn't work to drive
  the LCD display; need to use VIN. But according to [this
  article](https://support.arduino.cc/hc/en-us/articles/360014779679-About-Nano-boards-with-disabled-5-V-pins),
  if you short the two pads next to that pin, and if you power the
  board with the USB connection, you can get 5V output
