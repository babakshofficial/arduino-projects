# Arduino Projects by Babak Shahriari

Welcome to my Arduino Projects repository! This collection showcases a variety of projects I've developed, exploring the diverse applications of Arduino in both simple and complex environments. Below, you’ll find an overview of each project, including a brief description, components used, and instructions to get you started.

## Table of Contents

1. [Project 1: LED Blinking](#project-1-led-blinking)
2. [Project 2: Temperature and Humidity Monitor](#project-2-temperature-and-humidity-monitor)
3. [Project 3: Smart Home Automation](#project-3-smart-home-automation)
4. [Project 4: Ultrasonic Distance Sensor](#project-4-ultrasonic-distance-sensor)
5. [Project 5: Bluetooth Controlled Robot](#project-5-bluetooth-controlled-robot)

## Project 1: LED Blinking

**Description:**
A simple introductory project to get familiar with Arduino basics by blinking an LED.

**Components:**
- Arduino Uno
- LED
- Resistor (220Ω)
- Breadboard
- Jumper wires

**Instructions:**
1. Connect the LED to pin 13 on the Arduino.
2. Use the provided code in `led_blink.ino` to program the Arduino.

## Project 2: Temperature and Humidity Monitor

**Description:**
Monitor the environmental conditions using a DHT11 sensor and display the readings on an LCD.

**Components:**
- Arduino Uno
- DHT11 Sensor
- LCD Display
- Breadboard
- Jumper wires

**Instructions:**
1. Connect the DHT11 sensor to the Arduino.
2. Connect the LCD display.
3. Upload the code from `temp_humidity_monitor.ino`.

## Project 3: Smart Home Automation

**Description:**
Control home appliances using a relay module and Arduino for smart automation.

**Components:**
- Arduino Uno
- Relay Module
- Appliances (e.g., lamp)
- Breadboard
- Jumper wires

**Instructions:**
1. Wire the relay module to the Arduino.
2. Connect the appliances to the relay.
3. Upload `home_automation.ino` to the Arduino.

## Project 4: Ultrasonic Distance Sensor

**Description:**
Measure distances using an HC-SR04 ultrasonic sensor and display the results on a serial monitor.

**Components:**
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Breadboard
- Jumper wires

**Instructions:**
1. Connect the HC-SR04 to the Arduino.
2. Upload the code in `ultrasonic_distance.ino`.

## Project 5: Bluetooth Controlled Robot

**Description:**
Build a robot controlled via Bluetooth using an Android app.

**Components:**
- Arduino Uno
- Bluetooth Module (HC-05)
- Motor Driver (L298N)
- Motors and Wheels
- Robot Chassis
- Breadboard
- Jumper wires

**Instructions:**
1. Assemble the robot chassis and attach the motors.
2. Connect the Bluetooth module and motor driver to the Arduino.
3. Upload `bluetooth_robot.ino`.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/babakshofficial/arduino-projects.git
cd arduino-projects
Upload the relevant .ino files to your Arduino board using the Arduino IDE, and follow the instructions provided in each project's section.
