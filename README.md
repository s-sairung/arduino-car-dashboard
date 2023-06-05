# Arduino Car Dashboard 🚗💻
This project was inspired by a non-functional odometer in my Mitsubishi Galant E33A car model. Since this car model does not have an On-Board Diagnostics (OBD) port available, I initially attempted to use the Vehicle Speed Sensor (VSS) wire as an input for the Arduino board. However, I encountered several challenges, including random background noise and difficulty in accessing the wire. To overcome these issues, I have now adopted a GPS module as the input source for the Arduino, which allows for more reliable data.

# Current Features
- OLED odometer display with moving digits (like mechanical odometers)
- Accurate distance tracking using GPS coordinates

# Hardwares
- Arduino UNO R3
- GY-NEO6MV2 GPS Module
- 128X64 OLED Display

# Libraries
- [U8g2](https://github.com/olikraus/u8g2)
- [TinyGPSPlus](https://github.com/mikalhart/TinyGPSPlus)
- [EEPROMEx](https://github.com/thijse/Arduino-EEPROMEx)
