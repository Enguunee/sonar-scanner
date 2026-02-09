# Ultrasonic Sonar Scanner

Arduino-based embedded system that scans surroundings using an ultrasonic distance sensor mounted on a servo motor and provides real-time distance feedback.

## Overview
An ultrasonic sensor sweeps across angles using a servo motor to measure distances at multiple directions.

Servo rotates → distance measured  
Distance mapped → visual and audio feedback  

Creates a simple real-time scanning system similar to basic radar/sonar behavior.

## Features
- Angle-based distance scanning
- Servo motor sweep control
- Real-time distance measurement
- LED color feedback based on proximity
- Buzzer alerts for close objects
- Continuous sensor polling

## Tech Stack
- Arduino (C++)
- Ultrasonic sensor (HC-SR04)
- Servo motor control
- Analog/Digital I/O
- Real-time loop logic

## How It Works
1. Servo rotates to target angle  
2. Ultrasonic sensor sends pulse  
3. Echo time converted to distance  
4. Distance mapped to LED/buzzer output  
5. Process repeats for continuous scanning  

## Repository Structure
- `sonar.ino` – main firmware

## Demo
| Live Scanning Demo |
|-------------------|
| <img src="sonar_scanner.gif" width="450"> |
