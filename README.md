# IoT Smart Electricity Energy Meter

## Overview
This project implements an IoT-based energy meter using ESP32, voltage/current sensors, and Blynk for real-time monitoring of electricity usage.

## Components
- ESP32 Wi-Fi Board
- ZMPT101B Voltage Sensor
- SCT-013-030 Current Sensor
- 20x4 I2C LCD Display
- Resistors & Capacitors

## Circuit
The sensors connect to ESP32 analog pins, enabling voltage and current readings. The output is displayed on the LCD and sent to Blynk for remote monitoring.

## Features
- Real-time monitoring via Blynk (Web and Mobile)
- Displays Vrms, Irms, Power, and kWh
- Data stored in ESP32 EEPROM during power outages

## How to Use
1. Assemble the circuit as per the provided diagram.
2. Set up Blynk Dashboard for remote monitoring.
3. Upload the source code to ESP32 and monitor energy consumption in real-time.

## Conclusion
This system automates electricity monitoring, improves energy efficiency, and eliminates manual readings.

---

For full details, visit the [project page](https://nihal444.github.io/iot-project/).
