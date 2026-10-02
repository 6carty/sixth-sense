# Sixth Sense

**Anansi: an autonomous six-legged robot that sees, walks and finds its way.**

Meet Anansi, a hexapod robot built on the Freenove FNK0052 kit and a Raspberry Pi 4, named after the clever spider of West African and Caribbean folklore. This project documents her build from the first servo to full autonomy, including object detection, visual navigation and a port to ROS 2.

## Goals
- Assemble and calibrate the robot
- Get it walking via remote control
- Add autonomous obstacle avoidance
- Add camera-based object detection and tracking
- Move autonomously towards identified objects
- Port to ROS 2

## Progress
- [x] Leg and Servo Assembly
- [ ] Body and Electronics
- [ ] Software Setup
- [ ] Module tests
- [ ] Calibration and First Walk
- [ ] Custom Features

## Build log
See [/build-log](build-log) for dated entries with photos, notes and lessons learnt.

## Hardware
- Freenove Big Hexapod Robot Kit (FNK0052)
- Raspberry Pi 4
- 18 servos
- Camera module
- Ultrasonic distance sensor
- MPU6050 balance sensor

## Original kit code
The base code is provided by Freenove:
https://github.com/Freenove/Freenove_Big_Hexapod_Robot_Kit_for_Raspberry_Pi

All custom code in this repository is my own.
