# Bluetooth Controlled Car with Arduino and HC-05

This project demonstrates how to build a Bluetooth-controlled car using an Arduino and an HC-05 Bluetooth module. With this setup, you can control the movement of the car using a smartphone or any other Bluetooth-enabled device. 

## Components Required
- Arduino board (e.g., Arduino Uno)
- HC-05 Bluetooth module
- Motor driver module (e.g., L298N)
- DC motors (2x)
- Chassis for the car
- Wheels (2x)
- Battery or power source
- Jumper wires
- Android smartphone with Bluetooth

## Circuit Diagram

![](https://github.com/DevAdvancer/Bluetooth-Control-Car/blob/main/Bluetooth_Car_Circuit_Diagram.png)
## Wiring Instructions
1. Connect the motors to the motor driver module.
2. Connect the motor driver module to the Arduino.
3. Connect the HC-05 Bluetooth module to the Arduino.

## Usage
1. Power up the car using a suitable power source.
2. Pair your smartphone with the HC-05 Bluetooth module.
3. Open a Bluetooth terminal app on your smartphone.
4. Send the following commands to control the car:
   - 'F' for forward
   - 'B' for backward
   - 'L' for left
   - 'R' for right
   - 'S' for stop

## Author
Abhirup Kumar
Developed under Adamas Robotics & AI Club
