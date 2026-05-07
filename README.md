# Smart Garden Monitoring System Using FreeRTOS

An embedded IoT system for environmental monitoring and automated garden management using FreeRTOS-based multitasking. The project combines sensor data acquisition, real-time task scheduling, and wireless communication for smart agriculture applications.

## Overview

This project was developed to monitor environmental conditions in a smart garden environment using embedded systems and multitasking firmware. The system focuses on collecting sensor data, managing multiple tasks concurrently, and supporting real-time monitoring.

## Main Features

- Read and process environmental sensor data
- Monitor temperature, humidity, and soil conditions in real time
- Implement multitasking using FreeRTOS
- Support wireless communication for remote monitoring
- Display system status and sensor values
- Improve task responsiveness and system stability

## Hardware / Platforms

- STM32
- ESP32
- Environmental sensors
- Soil moisture sensor
- LCD I2C display
- Wireless communication module

## Interfaces and Communication

- GPIO
- UART
- I2C
- WiFi

## System Architecture

- **STM32**: handles sensor acquisition and FreeRTOS task scheduling  
- **ESP32**: provides wireless communication and IoT connectivity  
- **Sensors**: collect environmental and soil condition data  
- **LCD**: displays local monitoring information and system status  

## Development Tools

- STM32CubeMX
- Keil uVision / Embedded C
- Arduino IDE
- FreeRTOS

## My Responsibilities

- Developed multitasking embedded firmware using FreeRTOS
- Implemented sensor acquisition and environmental monitoring
- Integrated communication between embedded modules
- Supported testing, debugging, and system integration
- Improved task scheduling and real-time system responsiveness

## Result

The system can monitor environmental conditions, manage multiple embedded tasks concurrently, and support wireless monitoring through IoT communication. It demonstrates practical experience in FreeRTOS, embedded firmware development, sensor interfacing, and real-time system integration.

## Future Improvements

- Add automated irrigation control
- Improve sensor calibration and measurement accuracy
- Integrate cloud dashboard or mobile application
- Expand support for additional environmental sensors
- Optimize power consumption for long-term deployment
