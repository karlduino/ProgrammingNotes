## Adafruit ESP32-S3 TFT

See tutorial at
[adafruit](https://learn.adafruit.com/adafruit-esp32-s2-tft-feather/arduino-ide-setup)

- Needed to go to Arduino IDE preferences and add an additional board
  manager URL, <https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json>

- Needed to install pip

  ```shell
  sudo apt install python3-pip
  ```

- Needed to install pyserial

  ```shell
  pip install pyserial
  ```

- Make sure you install the right board (Adafruit ESP32-S3 TFT)

- then stuff worked. After uploading a sketch, need to click the reset
  button before it would run
