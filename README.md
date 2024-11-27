# EECS-113 Final Project: Building Management System

This project demonstrates a **Building Management System (BMS)** implemented using a Raspberry Pi 3B+ and various sensors to enhance energy efficiency, comfort, and safety in indoor environments.

## Overview

The BMS integrates hardware, software, and external APIs to monitor and control environmental conditions within a building. Key components include:

- **PIR Infrared Motion Detector with LED Indicator**: Detects heat signatures emitted by humans.
- **DHT-11 Sensor**: Measures temperature and humidity.
- **CIMIS API Integration**: Retrieves external weather data (e.g., humidity) for more accurate environmental monitoring.
- **HVAC Control**: Optimizes heating, ventilation, and air conditioning based on target temperature and current conditions.
- **Door/Window Sensors**: Monitors openings to prevent energy loss.
- **Fire Alarm System**: Activates alarms and safety protocols when potential fire risks are detected.

---

## Features

### 1. **Environmental Monitoring**
   - Sensors continuously collect indoor temperature and humidity data.
   - External weather data is fetched using the **CIMIS API** for enhanced accuracy.

### 2. **HVAC Control**
   - Adjusts HVAC system operations based on:
     - Target indoor temperature.
     - Current indoor/outdoor climate conditions.
   - Displays real-time status on an **LCD screen**.
   - **Energy Consumption Monitoring**: Calculates and displays energy usage and associated costs.

### 3. **Door/Window Management**
   - Automatically turns off the HVAC system when an open door or window is detected to minimize energy waste.

### 4. **Fire Alarm System**
   - Activates the alarm and opens doors/windows during fire emergencies.
   - Provides visual and audible alerts through:
     - LEDs
     - LCD screen notifications

### 5. **User Interaction**
   - Users can adjust target temperatures via physical buttons.
   - The system provides instant feedback on the LCD screen.

---

## Benefits

- **Energy Efficiency**: Reduces energy consumption by optimizing HVAC usage and minimizing waste.
- **User Comfort**: Maintains a comfortable indoor climate with precise control.
- **Safety**: Includes fire alarm and window/door monitoring for enhanced security.
- **Cost Monitoring**: Provides insights into energy costs, helping users save on bills.

---

## Hardware and Software

- **Hardware Components**:
  - Raspberry Pi 3B+
  - PIR Infrared Motion Sensor with LED Indicator
  - DHT-11 Temperature and Humidity Sensor
  - Door/Window Sensors
  - LCD Screen
  - Buttons and LEDs

- **Software/Tools**:
  - Python-based control algorithms
  - CIMIS API for weather data
  - Integration of sensor data for intelligent decision-making

---

## Project Video

[Watch the project demo here](https://youtu.be/SmSUwGY7VRM)

---

## How It Works

1. **Environmental Data**: Indoor data is collected via sensors, and outdoor data is fetched using the CIMIS API.
2. **HVAC Optimization**: Adjusts HVAC system settings based on real-time environmental data.
3. **Energy Monitoring**: Tracks energy consumption and provides cost calculations.
4. **Safety Features**:
   - Fire alarms trigger emergency protocols.
   - HVAC shuts down during door/window openings to avoid energy loss.

---

## Conclusion

This project demonstrates the potential of integrating sensors, APIs, and control algorithms to create an intelligent Building Management System. By optimizing energy efficiency, ensuring safety, and enhancing comfort, the BMS serves as a scalable solution for modern building automation.
