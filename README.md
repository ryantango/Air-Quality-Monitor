# Air-Quality-Monitor
ESP32-based environmental monitoring system for real-time measurement of CO₂, temperature, humidity, and atmospheric pressure using integrated digital sensors and a custom enclosure.
# ESP32 Air Quality Monitor

An ESP32-based environmental monitoring system designed to measure and display
real-time indoor air-quality and environmental conditions.

The system integrates multiple digital sensors to monitor:

- CO₂ concentration
- Temperature
- Relative humidity
- Atmospheric pressure

The project was developed to gain hands-on experience with embedded systems,
sensor integration, I²C communication, hardware debugging, and physical device
prototyping.

## System Overview

Environmental Sensors
        ↓
      I²C
        ↓
      ESP32
        ↓
Data Processing
        ↓
Environmental Measurements

## Features

- Real-time environmental monitoring
- Multiple sensor integration
- ESP32 microcontroller
- I²C sensor communication
- CO₂ measurement
- Temperature and humidity measurement
- Atmospheric pressure measurement
- Custom perfboard hardware implementation
- Custom-designed enclosure

## Hardware

The system consists of:

- ESP32 development board
- CO₂ sensor
- Temperature/humidity sensor
- Atmospheric pressure sensor
- Perfboard
- Supporting wiring and connectors
- Custom enclosure

## Firmware

The firmware is written in C/C++ using the Arduino development environment.

The ESP32:

1. Initializes each connected sensor.
2. Communicates with sensors using I²C.
3. Periodically acquires environmental measurements.
4. Processes the sensor readings.
5. Outputs the measurements for real-time monitoring.

## Engineering Challenges

Several challenges were encountered during development, including:

- Configuring multiple I²C devices
- Interpreting sensor datasheets
- Verifying sensor power requirements
- Debugging wiring and communication issues
- Integrating multiple components onto perfboard
- Packaging the electronics into a compact enclosure

Troubleshooting these issues helped improve my understanding of embedded
hardware/software integration and systematic engineering debugging.

## Skills Demonstrated

- ESP32 development
- Embedded C/C++
- Sensor integration
- I²C communication
- Circuit prototyping
- Datasheet interpretation
- Hardware debugging
- Soldering
- Environmental sensing
- CAD/enclosure design
- System integration

## Future Improvements

Potential future improvements include:

- Wi-Fi data transmission
- Cloud-based environmental data logging
- Historical data visualization
- Mobile/web dashboard
- Air-quality threshold alerts
- PCB integration
- Improved sensor calibration
- Battery-powered operation

## Project Status

Prototype completed. Future development will focus on improving data logging,
wireless connectivity, and hardware integration.
