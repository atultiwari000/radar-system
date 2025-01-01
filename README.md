# Radar System Using Arduino Nano and Processing

## Overview
This project demonstrates how to create a radar-like system using an **ultrasonic sensor (HC-SR04)** and a **servo motor** with **Arduino Nano** for distance detection and **Processing** for graphical visualization. The radar scans for objects and displays their position in real-time, similar to radar systems used in submarines or aircraft.

---

## Features
- Real-time object detection using an ultrasonic sensor.
- Servo-controlled radar sweep for a 180-degree field of view.
- Graphical interface in Processing, simulating a radar screen with arcs, lines, and object markers.
- Serial communication between Arduino and Processing for seamless data transfer.

---

## Components Required

| **Component**          | **Quantity** |
|-------------------------|--------------|
| Arduino Nano            | 1            |
| HC-SR04 Ultrasonic Sensor | 1          |
| Servo Motor             | 1            |
| USB Cable               | 1            |

---

## Wiring Diagram
### **Ultrasonic Sensor (HC-SR04):**
- **VCC** → Arduino 5V
- **GND** → Arduino GND
- **Trigger (Trig)** → Arduino Pin D9
- **Echo** → Arduino Pin D10

### **Servo Motor:**
- **Signal** → Arduino Pin D8
- **VCC** → Arduino 5V
- **GND** → Arduino GND

---

![WhatsApp Image 2025-01-01 at 23 10 33_ed959780](https://github.com/user-attachments/assets/0c57cf84-f507-4be0-b9c3-7e96ce67e497)
![WhatsApp Image 2025-01-01 at 23 10 33_969c0fc8](https://github.com/user-attachments/assets/6d30ce64-7db8-41bc-8fcd-e492c96322bf)
