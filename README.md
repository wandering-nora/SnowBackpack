# SnowBackpack
Cute ESP32-C3 backpack for a 2 x n [SnowPixel](https://github.com/wandering-nora/SnowPixel) matrix display.

This board can power a grid of 2+ SnowPixel displays without any wiring in a thin package.

The main features are:
- ESP8685H4 mcu with 4MB of flash, Wifi and BLE
- Battery charging for protected 1s lipo cells
- ST LSM6DSO 6-axis low power accelerometer
- Efficient 5V boost converter with 500mA max current for the SnowPixel modules
- On board ceramic antenna


<img src="./images/snowbackpack.png" style="width: 100%; height: auto;" />


## Drawbacks 
The part selection was not done with budget in mind as this is mainly a project to mess around with fancy chips.  
The boost converter drive current of 500mA can be somewhat limiting for bigger / bright outdoor displays.
