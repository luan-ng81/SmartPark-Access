# SmartPark-Access: Car Parking System Using Arduino UNO

## Project Overview

This project implements a smart car parking system using an Arduino UNO. The system automates gate control using a servo motor, counts available parking spots, and displays the information on an LCD with an I2C module. The IR sensor is used to detect cars entering and exiting the parking lot.

## Features

- Automatically opens and closes the gate for cars entering or exiting.
- Tracks the number of available parking spots in the lot.
- Displays the number of available spots on the LCD screen.

## Components Used

1. Arduino UNO
2. LCD Display with I2C Module: Used to display the number of available parking spots.
3. Servo Motor: Controls the gate's opening and closing mechanism.
4. IR Sensors: Detects vehicles entering and exiting the parking lot.

## Working Principle

1. Vehicle Detection:
- IR sensors are placed at the entrance and exit points of the parking lot.
- When a car is detected by the entrance sensor, the system checks for available spots.
2. Gate Control:
- If spots are available, the servo motor opens the gate.
- After the car passes, the gate closes automatically.
3. Spot Counting:
- The system maintains a counter to track the number of available parking spots.
- For every car that enters, the counter decrements.
- For every car that exits, the counter increments.
4. LCD Display:
- The LCD display shows the current number of available spots in

## Circuit Diagram

Please check in the resource folder
