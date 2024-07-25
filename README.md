# Smart-Street-Light-system

This project demonstrates a smart street light system using Arduino, motion sensors, and IR sensors. The street lights are designed to turn on automatically when a vehicle passes through and turn off when no vehicles are detected, thus conserving energy and improving efficiency.

## Features

- Automatically turns on street lights upon detecting a vehicle using motion and IR sensors.
- Turns off street lights when no vehicles are detected to save energy.
- Arduino-based system for controlling and monitoring street light operations.

## Components Used

- Arduino Uno
- Motion Sensor (e.g., PIR sensor)
- IR Sensor
- LED Lights 
- Jumper wires

<img src="https://github.com/TasmiyaChaman/Smart-Street-Light-system/blob/main/Functioning%20%20of%20Smart%20street%20light.jpeg" alt="Schematics" width="1000" height="600">
<p>Figure 1: Functioning of Smart street light.</p>

## Installation

1. **Arduino Setup**: 
   - Connect the motion sensor and IR sensor to the Arduino Uno following the wiring diagram.
   - Ensure all connections are secure and correct to avoid any malfunction.

2. **Upload Code**:
   - Upload the Arduino sketch to your Arduino board using the Arduino IDE.

3. **Hardware Integration**:
   - Connect the relay module to control the street lights. Ensure the connections are made as per the relay module's specifications.

4. **Testing**:
   - Power up the Arduino board and observe the behavior of the street lights as vehicles pass through and move away from the sensors.

<img src="https://github.com/TasmiyaChaman/Smart-Street-Light-system/blob/main/Working%20Model.jpeg" alt="Schematics" width="1000" height="600">
<p>Figure 1: Working model of Smart street light.</p>

## Usage

- Once the system is set up and powered, the street lights will automatically turn on when a vehicle is detected by the motion and IR sensors.
- They will remain on as long as there is vehicle activity detected.
- When no vehicles are detected for a specified period, the street lights will automatically turn off to conserve energy.
