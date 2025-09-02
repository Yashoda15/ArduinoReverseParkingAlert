# Arduino Reverse Parking Alert System

A simple **Arduino-based Reverse Parking Alert System** that detects obstacles while reversing and alerts the driver using a buzzer. The system uses an ultrasonic sensor to measure distance and sounds an alarm when an object comes too close.

---

## Components Needed

- Arduino Uno (or compatible board)  
- HC-SR04 Ultrasonic Sensor  
- Buzzer  
- Jumper Wires  
- Breadboard (optional)  

---

## Wiring Guide

| Component        | Arduino Pin |
|-----------------|-------------|
| Ultrasonic Trig  | 3           |
| Ultrasonic Echo  | 2           |
| Buzzer           | 6           |
| GND              | GND         |
| VCC              | 5V          |

---

## Features

- Detects objects up to 30 cm behind the vehicle.  
- Alerts the driver using a buzzer.  
- Prints distance readings to the Serial Monitor.  
- Easy to assemble and use.  

---

## How to Use

1. Connect the components as shown in the wiring guide.  
2. Upload `ReverseParkingAlert.ino` to your Arduino using the Arduino IDE.  
3. Open the Serial Monitor at 9600 baud to monitor distance readings.  
4. Move an object behind the sensor. The buzzer will sound when it is closer than 30 cm.

---

## Example Output

