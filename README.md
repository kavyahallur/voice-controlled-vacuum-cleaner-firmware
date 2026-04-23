# Voice-Controlled Automatic Vacuum Cleaner Firmware (ATmega328)

## Overview
Designed an embedded system for a voice-controlled automatic vacuum cleaner using the ATmega328 microcontroller. The system integrates Bluetooth communication, motor control, and sensor feedback to enable real-time operation.

---

## System Workflow
1. Voice command issued via Android application  
2. Command transmitted through Bluetooth (UART protocol)  
3. ATmega328 processes incoming data  
4. Motor driver executes movement instructions  
5. Sensors provide real-time feedback for control  

---

## Key Features
- UART-based Bluetooth communication for command handling  
- Real-time motor control using embedded firmware logic  
- Integration of multiple sensors (IR/Ultrasonic)  
- Debugging of firmware-hardware interaction using serial communication  

---

## Hardware Components
- ATmega328 Microcontroller  
- Bluetooth Module (HC-05/HC-06)  
- Motor Driver (L298N or equivalent)  
- Sensors (IR / Ultrasonic)  
- Power Supply  

---

## 🏗️ System Architecture
![Architecture](architecture.png)

---

## System Design
The system was designed with a modular approach, separating communication, control, and sensing layers to ensure efficient real-time performance and easier debugging.

---

## Key Learnings
- Embedded firmware development using C  
- UART communication and debugging techniques  
- Hardware-software integration in real-time systems  
- Designing modular embedded architectures  

---

## Note
This repository focuses on system design, architecture, and implementation approach. Source code is not included.
