# esp32_control_example
practice programming the ESP32 MCU

# Refer
https://www.humix.com/@esp32io_com/v/esp32-controls-servo-motor-via-websocket

# ESP32 DevKit Doc.
https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_cn.pdf

# Arduino IDE 2
## Download the Arduino IDE
```
https://www.arduino.cc/en/software/
```
## ESP32 json file
- Launch the Arduino IDE > File > Preferences > Additional boards manager URLs > Paste the ESP32 json file as below > OK
```
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
```
## Update ESP32 board config
- Tools > Board > Borads Manager > search "ESP" > find the "ESP32 by Espressif system" > INSTALL or UPDATE > 
## Select your own board, Ex: ESP32-WROOM-32
- Tools > Board > esp32 > ESP32 Dev Module
## Compile & flash to target board
- Tools > port > select your COM number
- Sketch > Verify/Compile > Upload
