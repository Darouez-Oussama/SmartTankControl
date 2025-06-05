# Smart Tank Control System with Arduino Cloud

This project implements an automated water tank monitoring and pump control system using Arduino Cloud. The system monitors the water level in a tank and automatically adjusts the pump voltage to maintain optimal water levels.

## Overview

This smart tank control system utilizes Arduino Cloud to create an automated water management solution. It provides real-time monitoring of tank water levels and intelligent pump control, allowing for efficient water management and preventing tank overflow or dry running of the pump.

## Features

- Real-time water tank level monitoring
- Automatic pump voltage adjustment based on tank level
- Remote monitoring through Arduino Cloud dashboard
- Mobile access via Arduino IoT Cloud Remote app
- Real-time data visualization of tank levels and pump performance

## Hardware Requirements

- Arduino IoT Cloud account
- Compatible Arduino board (e.g., Arduino Nano 33 IoT, MKR WiFi 1010, etc.) or ESP32 
- Water level sensor
- Water pump with voltage control capability
- Power supply for the pump
- Connecting wires and mounting hardware

## Setup

1. **Arduino Cloud Account**
   - Sign up for an Arduino Cloud account at [Arduino Cloud](https://cloud.arduino.cc/)
   - Create a new "Thing" in your Arduino Cloud dashboard

2. **Hardware Setup**
   - Connect the water level sensor to your Arduino/ESP32 board
   - Wire the pump control circuit
   - Install the Arduino Create Agent
   - Configure your board in Arduino Cloud

3. **Network Configuration**
   - Configure your WiFi credentials in the Arduino Cloud dashboard
   - Ensure your board has internet connectivity

## System Operation

1. **Tank Level Monitoring**
   - The system continuously monitors the water level in the tank
   - Real-time level data is transmitted to Arduino Cloud
   - Historical data is available for analysis

2. **Pump Control**
   - Pump voltage is automatically adjusted based on tank level
   - Prevents overflow and dry running conditions
   - Manual override available through the dashboard

3. **Dashboard Access**
   - Monitor tank levels in real-time
   - View pump operation status
   - Access historical data and performance metrics
   - Control pump operation manually when needed

4. **Mobile Access**
   - Download the Arduino IoT Cloud Remote app
   - Log in with your Arduino Cloud credentials
   - Monitor and control your system on the go

## Safety Features

- Automatic pump shutdown if tank level is too low
- Overflow prevention
- System status notifications
- Emergency stop function

## Support

For any questions or issues:
- Check the [Arduino Cloud Documentation](https://docs.arduino.cc/arduino-cloud/)
- Visit the [Arduino Forum](https://forum.arduino.cc/)

