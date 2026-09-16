# Smart Bot 

A computer-vision-based mobile robot designed to detect and follow a user-selected object. The project combines object detection, wireless communication, motor control, and a compact mobile robotic platform.

## Overview

The Smart Bot was developed as a team project to explore the integration of computer vision with a physical mobile robot. A camera captures the surroundings and YOLOv8 is used for object detection. The selected object is tracked and the corresponding movement commands are sent to the robot through Bluetooth.

The robot uses an Arduino-based control system with a TB6612FNG motor driver and two N20 geared motors for movement.

## System Flow

**Camera → Object Detection → Target Selection/Tracking → Movement Commands → Bluetooth → Arduino → Motor Driver → Motors**

## Hardware

* Arduino
* TB6612FNG Motor Driver
* 2 × N20 Geared Motors
* HC-05 Bluetooth Module
* Robot chassis and wheels
* Battery and power circuitry
* Camera/phone camera for vision input

## Software & Technologies

* Python
* YOLOv8
* Computer Vision
* Arduino
* Bluetooth Communication
* Motor Control

## My Contribution

As part of the team, I mainly worked on the hardware and physical design of the robot.

* Designed and assembled the robot chassis
* Worked on motor and motor-driver integration
* Planned and implemented the wiring and power connections
* Integrated the Arduino with the motor-control system
* Worked on the physical placement of electronics and components
* Tested motor movement and hardware communication
* Helped integrate the vision and control system with the physical robot
* Troubleshot hardware and assembly issues during testing

## Key Features

* Object detection using YOLOv8
* Tracking of the selected target
* Wireless command transmission using Bluetooth
* Differential-drive movement
* Compact two-wheel robotic platform
* Integration of computer vision with embedded hardware

## Learning Outcomes

This project gave us practical experience in connecting computer vision with a physical robotic system. It also involved hands-on work with motor drivers, embedded controllers, Bluetooth communication, wiring, mechanical assembly, and debugging a complete hardware-software system.

## Project Type

Team Project | Robotics | Computer Vision | Embedded Systems

