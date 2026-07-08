# STM32-Based Smart Spirometer

## Project Overview

The Smart Spirometer is a portable embedded system developed for respiratory monitoring and lung-capacity estimation.

The system uses an STM32F103C8T6 microcontroller, a BMP280 pressure sensor, and IR sensors to monitor exhalation and detect predefined lung-capacity levels.

## Hardware Used

- STM32F103C8T6
- BMP280 Pressure Sensor
- IR Sensors
- 16x2 LCD Display
- Spirometer Tube and Airflow Assembly

## Software and Tools

- Embedded C/C++
- Arduino IDE
- STM32
- Git and GitHub

## Communication Protocols

- I2C for BMP280 sensor communication
- GPIO for IR sensor interfacing
- GPIO-based LCD interfacing

## Working Principle

The user exhales into the spirometer tube. The BMP280 sensor detects pressure variations during exhalation and transfers the sensor data to the STM32.

IR sensors are used to detect predefined lung-capacity thresholds of 600 ml, 900 ml, and 1200 ml.

The STM32 processes the sensor data and displays the detected lung-capacity level on a 16x2 LCD.

## My Contribution

I contributed to STM32 sensor interfacing, hardware integration, sensor calibration, and prototype testing.

I worked on integrating the BMP280 pressure sensor and IR sensors with the STM32 microcontroller and understanding I2C communication and GPIO-based sensor acquisition.

I also contributed to system testing, result analysis, and technical documentation.

## Key Learning

This project helped me gain practical experience in:

- STM32-based embedded system development
- Sensor interfacing
- I2C communication
- GPIO handling
- Hardware-software integration
- Embedded system testing

## Applications

- Respiratory monitoring
- Home-based lung monitoring
- Respiratory rehabilitation
- Portable healthcare systems

## Project Documentation

The complete project report is available in this repository.

