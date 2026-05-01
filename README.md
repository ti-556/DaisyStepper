# DaisyStepper
This repo aims to create a PCB module that allows easy daisy chain of miniature stepper motors. Daisy chain allows easier expansion and cable management, especially for certain types of robots like a robot arm or a humanoid. This module is best for hobby miniature robotics, like a miniature robot arm or tabletop companion robot. 

## How It Works
The module consists of an **attiny1616** 8bit AVR microcontroller and a **drv8833** dual H-bridge motor driver. The attiny1616 microcontroller acts as a I2C slave device that actuates a miniature stepper motor via the drv8833 motor driver based on motor comands received from an I2C master device (e.g. Arduino, ESP32...).  

