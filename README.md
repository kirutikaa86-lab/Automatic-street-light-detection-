# Smart Space Management using IoT (Automatic Lighting System)

## Overview

This project demonstrates a simple Smart Space Management system using IoT concepts. It focuses on automatic lighting control based on environmental light conditions.

The system uses a Light Dependent Resistor (LDR) to detect ambient light and automatically turns an LED ON or OFF. This helps in reducing energy consumption and improving efficiency in smart environments.

## Components Used

* Arduino Uno
* LDR (Light Sensor)
* LED
* Resistor (1k ohm)
* Connecting wires

## Working Principle

The LDR sensor measures the intensity of light in the surroundings.

* When the environment is dark, the LDR value decreases, and the system turns ON the LED.
* When there is sufficient light, the LED turns OFF automatically.

This creates an automated lighting system without human intervention.

## Circuit Description

* LDR is connected to analog pin A0
* LED is connected to digital pin 13 through a resistor
* Arduino processes sensor data and controls the LED output

## Features

* Automatic light control
* Energy efficient system
* Simple and low-cost design
* Suitable for smart homes and smart street lighting

## Simulation

This project was designed and tested using the Wokwi simulator.

## Live Simulation

https://wokwi.com/projects/461288032267489281

## Applications

* Smart street lights
* Home automation systems
* Office energy management
* Smart city infrastructure

## Future Improvements

* Add motion sensor (PIR) for better automation
* Integrate with IoT cloud platforms
* Mobile app control
* Smart scheduling system

## Conclusion

This project shows how basic IoT components can be used to create intelligent and automated systems for smart space management. It is a simple yet effective solution for improving energy efficiency.
