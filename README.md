# Solar-Powered Smart Home Automation System

## Overview

This project presents an energy-efficient smart home automation system powered by solar energy. The system optimizes power consumption by intelligently controlling lighting, ventilation, air conditioning, and security based on environmental conditions and human presence detection. The whole project is designed

### Technologies
Microcontroller: Arduino
Designing Software and Programming language: TinkerCAD and C/C++

## Features

### **Automatic Door Control**
- Ultrasonic sensor detects person presence within 320cm range
- Servo motor automatically opens door when person approaches
- Safety timer closes door after 5-6 seconds delay

### **Smart Lighting System**
- Motion sensor detects occupancy in rooms
- Photoresistor measures ambient light intensity
- Lights activate only during nighttime or low-light conditions
- Energy optimization through conditional lighting

### **Climate Control**
- Automatic fan activation upon motion detection
- Temperature-based AC control with optimized constant speed operation
- Energy-efficient climate management

### **Safety Monitoring**
- Smoke sensor with 4-level detection system:
  - Low
  - Medium  
  - High
  - Exit (Critical/Hazardous)
- Integrated buzzer alert system for smoke detection

### **Real-time Display**
- LCD display showing:
  - Distance measurement from ultrasonic sensor
  - Current smoke levels
  - Light status (ON/OFF)
  - Temperature readings

 <img src="System Architecture/SystemArchitecture.png" alt="Alt text" width="500" height="300" />

## Energy Optimization Features

- **Conditional Operation**: Devices activate only when needed
- **Solar Power Integration**: Renewable energy source
- **Smart Scheduling**: Light control based on natural light availability
- **Efficient Climate Control**: Optimized AC operation speeds
- **Motion-Based Activation**: Reduces unnecessary power consumption

## Safety Features

- **Multi-level Smoke Detection**: Early warning system
- **Automatic Door Closure**: Security and energy conservation
- **Temperature Monitoring**: Prevents overheating
- **Alert System**: Immediate notification of hazardous conditions

## Usage

1. **System Startup**: Solar panel charges battery and powers system
2. **Entry Detection**: Ultrasonic sensor triggers door opening
3. **Occupancy Sensing**: Motion sensor activates room systems
4. **Environmental Control**: Automatic lighting and climate adjustment
5. **Safety Monitoring**: Continuous smoke and temperature surveillance
6. **Status Display**: Real-time information on LCD screen

## Technical Specifications

| Component | Specification |
|-----------|---------------|
| Detection Range | 320cm (Ultrasonic) |
| Door Close Delay | 5-6 seconds |
| Smoke Levels | 4 modes (Low/Medium/High/Exit) |
| Power Source | Solar + Battery backup |
| Display Type | LCD with multi-parameter view |

