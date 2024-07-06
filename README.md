# Spatial_Mouse-ESP32-and-BMI160_IMU-based
Inspired by how Apple Vision pro Interface, this wireless mouse is created to emulate it using Boch's Accelerometer and ESP32 capacitive touch features

# Features
- Connect to esp32 using Bluetooth
- Control the mouse wirelessly
- Click button with the Mouse library and ESP32 capacitive touch feature (pin 9)

# Tech Required
- Esp32
- BMI160 Accelerometer/Gyroscope
- Arduino IDE or equivalent

# Connection Table
- ESP32   BMI160
- 3v3     VIN
- Gnd     Gnd
- 22      SCL
- 21      SDA
- 9 (wt finger)
