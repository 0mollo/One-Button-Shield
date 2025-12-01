![image alt](https://github.com/0mollo/One-Button-Shield/blob/main/One-button%20shield%20top%20view.png?raw=true) | ![image alt](https://github.com/0mollo/One-Button-Shield/blob/main/One-button%20shield%20bottom%20view.png?raw=true) |
# C3-Mini 1-Button Shield

The C3-Mini 1-Button Shield is a compact momentary push-button interface designed for the ESP32-C3 Mini board with a D1-Mini–compatible header layout.  
It allows simple and reliable digital input for user interactions such as triggering events, navigating menus, or selecting modes.

## Features
- Single tactile momentary push button
- D1 Mini–compatible dual-row header
- Default pin connection: **D3 → GPIO4**
- On-board pullup via microcontroller (no external resistor required)
- Operating voltage: **3.3V logic**
- Pass-through power headers for **5V** and **3.3V**
- PCB dimensions: **28 × 25.60 mm (approx.)**
- Compatible with ESP32-C3 Mini modules

## Documentation
- [Push button datasheet](https://github.com/0mollo/One-Button-Shield/blob/main/Push-Button.pdf)
- [One-button Shield Schematics](https://github.com/0mollo/One-Button-Shield/blob/main/One-button%20shield.pdf)
- [Arduino example](https://github.com/0mollo/One-Button-Shield/blob/main/One%20button%20shield%20arduino%20example.txt)

## Pin Mapping

| Shield Pin | MCU Pin | Function        |
|-----------|---------|-----------------|
| D3        | GPIO4   | Button Input    |
| GND       | GND     | Ground          |
| 5V        | 5V      | Power Pass-through |
| 3V3       | 3.3V    | Logic / Modules |


## Optional Libraries for Button-Controlled Actions
If the button interacts with peripherals, you might use:
- [Adafruit NeoPixel](https://docs.arduino.cc/libraries/adafruit-neopixel/) LED control
- [Adafruit SSD1306/GFX](https://docs.arduino.cc/libraries/adafruit-ssd1306/) If the button navigates an OLED Menu
- [Stepper/Servo Libraries](https://docs.arduino.cc/libraries/stepper/) if the button triggers movement
- [Preference/EEPROM](https://docs.arduino.cc/learn/built-in-libraries/eeprom/) saving states on button press
## License
MIT License (see LICENSE file)

