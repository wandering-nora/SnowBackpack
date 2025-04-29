# SnowBackpack
Cute ESP32-C3 backpack for 2 x n [SnowPixel](https://github.com/wandering-nora/SnowPixel) matrix displays.

This board can power a grid of 2+ SnowPixel displays without any wiring in a thin package.

The main features are:
- ESP8685H4 RISC-V mcu with 4MB of flash, Wifi and BLE @160MHz
- Battery charging for protected 1s lipo cells
- ST LSM6DSO 6-axis low power accelerometer
- Efficient 5V boost converter with 500mA max current for the SnowPixel modules
- Onboard ceramic antenna

The board has no power switch, the MCU can deep sleep and be woken up by the always on IMU with two interrupt pins. The 5V boost converter can also be switched off leaving only the 3.3V rail and IMU operational for very low static power consumption.

> Note:  for normal operation R13 and R14  are unpopulated

<img src="./images/snowbackpack.png" style="width: 100%; height: auto;" />

## Manufacturing update
After assembly with a hot plate everything works as intended ^_^  
There's only a couple of things I would change for V1.2 which should keep my stencil mostly reusable.

#### Todo for V1.2
- [ ] Get rid of jumper on data out pad
- [ ] Change battery connector to a 1A capable one
- [ ] Consider removing extra pads on long edge

