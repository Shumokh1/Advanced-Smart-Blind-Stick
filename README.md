# Advanced Smart Walking

## Introduction
An advanced smart walking stick designed to assist visually impaired users with navigation and obstacle detection using ultrasonic sensors, buzzer, vibration feedback, and a water sensor for slippery surfaces.

## Hardware Components
- Arduino Uno (ATmega328P microcontroller)  
- 3x HC-SR04 Ultrasonic Sensors (front, left, right)  
- Water Sensor (detects moisture)  
- Buzzer (audio alerts)  
- Vibration Motor (haptic feedback)  
- 9V Battery (power supply)  
- Connecting wires  

## Connections Overview
- Ultrasonic Sensors:  
  - VCC → 5V, GND → GND  
  - TRIG → Digital pins 9, 5, 7  
  - ECHO → Digital pins 10, 6, 8  
- Buzzer → Digital pin 11 (positive), GND  
- Vibration Motor → Digital pin 12, GND  
- Water Sensor → Analog input pin  
- 9V Battery → VIN & GND  

## Hardware Setup

### Arduino Virtual Connections  
<img src="https://github.com/Shumokh1/Advanced-Smart-Blind-Stick/raw/main/arduino.jpeg" width="350" />

### Physical Hardware  
<img src="https://github.com/Shumokh1/Advanced-Smart-Blind-Stick/raw/main/hwDemo.png" width="350" />
