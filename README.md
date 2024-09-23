# Radar Arduino Project

## Overview
This project implements a radar system using an Arduino board, an ultrasonic sensor, and a servo motor. The system rotates the ultrasonic sensor to measure distances at various angles and displays the data graphically using Processing software.

## Components Required
- Arduino board (e.g., Arduino Uno)
- Ultrasonic sensor (e.g., HC-SR04)
- Servo motor
- Jumper wires
- Breadboard (optional)

## Wiring Diagram
![Wiring Diagram](https://github.com/Omar-Rihani/Radar-Project/blob/main/Diagram.png)

## Instructions for Use
1. **Connect the Components:**
   - Refer to the wiring diagram to connect the ultrasonic sensor and servo motor to the Arduino board.
  
2. **Upload the Arduino Code:**
   - Use the Arduino IDE to write and upload the code that controls the servo and reads the ultrasonic sensor data.

3. **Run the Processing Sketch:**
   - Install the Processing software and open the provided sketch that visualizes the radar data. Ensure the correct COM port is specified in the sketch.

4. **Observe the Output:**
   - Watch the Processing window for distance and angle readings as the sensor rotates.

## Troubleshooting
- **Check Connections:** Ensure all components are properly connected as per the wiring diagram.
- **Verify Serial Communication:** Make sure the baud rate is consistent (e.g., 9600) in both Arduino and Processing codes.
- **COM Port Issues:** Confirm that the COM port specified in the Processing sketch matches the port assigned to the Arduino board.
