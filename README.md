# Car Parking Assistance System

## Overview
Welcome to the Car Parking Assistance System!  
This project enhances vehicle safety and convenience by detecting obstacles during parking using **ultrasonic sensors**.  
The system provides **real-time audio feedback** via a buzzer, helping drivers park with confidence and avoid collisions.

---

## Sub-Systems

### 1. Distance Measurement
- **Ultrasonic Sensor (HC-SR04)**: Continuously measures the distance between the car and obstacles.  
- **Microcontroller (ATmega / TM4C)**: Processes sensor data and triggers alerts.  

**Functionality**  
- Sends ultrasonic pulses and calculates distance based on echo return time.  
- Transfers distance data to the control unit for decision-making.  

---

### 2. Obstacle Alert System
- **Buzzer**: Provides real-time alerts.  
- **Proximity Feedback**:  
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
1. Clone this repository:
   ```bash
   git clone https://github.com/ZuAdham/Car_Parking_Assistance_System.git
