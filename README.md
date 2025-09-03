# Car Parking Assistance System

## Repo Description
Car Parking Assistance System using ultrasonic sensors and buzzer alerts, built on a microcontroller platform to enhance vehicle safety during parking.

---

## Overview
Welcome to the Car Parking Assistance System!  
This project enhances vehicle safety and convenience by detecting obstacles during parking using **ultrasonic sensors**.  
The system provides **real-time audio feedback** via a buzzer, helping drivers park with confidence and avoid collisions.

---

## Sub-Systems

### 1. Distance Measurement
- Ultrasonic Sensor (HC-SR04): Continuously measures the distance between the car and obstacles.  
- Microcontroller (ATmega / TM4C): Processes sensor data and triggers alerts.  

**Functionality**  
- Sends ultrasonic pulses and calculates distance based on echo return time.  
- Transfers distance data to the control unit for decision-making.  

---

### 2. Obstacle Alert System
- Buzzer: Provides real-time alerts.  
- Proximity Feedback:  
  - Slow beeps when obstacle is far.  
  - Faster beeps as the obstacle gets closer.  
  - Continuous beep when very close.  

---

## Components
- Ultrasonic Sensor (HC-SR04)  
- Microcontroller (ATmega / TM4C / your target platform)  
- Buzzer  
- Power Supply & Connections  

---

## Installation and Setup
1. Clone this repository from GitHub.  
2. Open the project in Eclipse IDE.  
3. Build and flash the firmware to your microcontroller.  
4. Connect the ultrasonic sensor and buzzer to the proper pins.  

---

## Usage
- Place an obstacle in front of the sensor.  
- Listen to buzzer feedback as the car moves closer.  
- Use the sound frequency to judge the safe parking distance.  

---

## Future Enhancements
- Add multiple ultrasonic sensors for side/rear detection.  
- Integrate LEDs for visual distance feedback.  
- Extend the system into a complete Smart Parking Solution.  
