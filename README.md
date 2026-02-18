🚦 Raspberry Pi Traffic Light Control using GPIOZero

This project simulates a real-world traffic light system using a Raspberry Pi and the GPIOZero library in Python. It controls three LEDs (Red, Amber, and Green) connected to GPIO pins to mimic actual traffic signal behavior.

📌 Overview

The program uses the TrafficLights class from the gpiozero library to manage three LEDs connected to GPIO pins 2 (Red), 3 (Amber), and 4 (Green). The system follows a standard traffic light sequence with timed intervals.

The cycle runs continuously using an infinite loop.

🔄 Working Principle

🟢 Green light turns ON for 10 seconds (vehicles move).

🟡 Amber light turns ON for 1 second (prepare to stop).

🔴 Red light turns ON for 10 seconds (vehicles stop).

🟡 Amber turns ON briefly before switching back to Green.

The cycle repeats indefinitely.

This simulates a basic real-time traffic control system.

🛠️ Hardware Requirements

Raspberry Pi

3 LEDs (Red, Yellow/Amber, Green)

3 Resistors (220Ω recommended)

Breadboard

Jumper wires

⚙️ Technologies Used

Python

GPIOZero library

Raspberry Pi GPIO pins

🎯 Learning Objectives

Understanding GPIO output control

Implementing timed sequences using sleep()

Using built-in GPIOZero device classes

Simulating real-world embedded systems

🚀 Applications

Educational demonstrations

Embedded systems practice

IoT and automation learning

Mini traffic signal models# Traffic-Light
