Car Reverse Alert System – Arduino Project

This project is a basic car reverse safety system built using Arduino, an ultrasonic sensor, 3 LEDs (Green, Yellow, Red), and a buzzer.
It visually and audibly alerts the driver based on the distance of obstacles behind the vehicle:

Green LED – Safe distance (> 50 cm)

Yellow LED – Caution (20–50 cm)

Red LED + Buzzer – Danger (< 20 cm)

Features:

Real-time obstacle detection using HC-SR04 ultrasonic sensor

Visual distance indication with 3 LEDs

Sound alert for close obstacles

Simple and beginner-friendly code

Hardware Used:

Arduino Uno

HC-SR04 Ultrasonic Sensor

3 LEDs (Green, Yellow, Red) + Resistors

Buzzer

Breadboard & Jumper Wires

How It Works:
The ultrasonic sensor measures distance.
Depending on the range:

50 cm → Green ON

20–50 cm → Yellow ON

<20 cm → Red + Buzzer ON
