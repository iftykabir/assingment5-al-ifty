# assignment5-template
Basics of programming assignment 5

## Student

Fill here:

- Al Jamiiul Kabir Ifty
- Turtle

## Description of the project

This repository contains the setup for the FoCar project. It includes the main entry script (`main.py`) pre-configured with core Python libraries required for data analysis, image processing, and sensor data handling.

## User instruction

FOCAR is a compact robot car controlled by a Raspberry Pi Pico, motor controller, DC motors, and an LED. The Pico sends control signals to the motor controller, which operates the motors. All components must be connected correctly, with a common GND between the Pico and motor controller. The robot is programmed in MicroPython using Pin, PWM, and sleep functions.

FOCAR supports forward, backward, left, right, and stop movements, as well as LED ON/OFF control. The motors must be connected to the motor controller, not directly to the Pico. If two Raspberry Pi Picos are used, they can communicate through UART using TX, RX, and a common GND connection.

Before operation, check all wiring and power connections. For initial testing, keep the wheels off the ground and test the LED and each movement function separately. If a motor rotates in the wrong direction, correct the motor wiring or software settings. Always stop the robot before changing any connections and operate FOCAR only after all functions have been safely tested.
