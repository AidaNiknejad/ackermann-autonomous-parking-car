# Ackermann Steering Autonomous Parking Car

A small-scale autonomous vehicle developed using an Ackermann steering mechanism and an Arduino Mega controller, with the ability to perform automatic parallel parking.

## Project Overview

This project focuses on the design and implementation of a small autonomous vehicle equipped with an Ackermann steering mechanism.

The main objective is to demonstrate practical vehicle control principles in confined environments and to implement a simple autonomous navigation system using affordable and accessible hardware.

The vehicle uses an Arduino Mega as its central processing unit. Environmental information is collected through multiple sensors, while electric motors are used to control the vehicle's movement and steering mechanism.

One of the main capabilities of the system is automatic parallel parking. The vehicle receives information from its surrounding environment, detects the available parking space, and performs the required movements to enter the parking position.

## Main Features

- Small-scale autonomous vehicle
- Ackermann steering mechanism
- Automatic parallel parking
- Arduino Mega as the central controller
- Environmental sensing
- Motor-based vehicle movement
- Steering angle control
- Autonomous maneuver execution
- Operation in confined environments
- Low-cost and accessible hardware implementation
- Modular hardware and software architecture

## Ackermann Steering Mechanism

The Ackermann steering mechanism allows the inner and outer front wheels to rotate at different steering angles during a turn.

This reduces wheel slipping and provides a more realistic and efficient turning motion compared to simple differential steering systems.

In this project, the Ackermann mechanism is used to reproduce the steering behavior of real vehicles on a smaller scale.

## Automatic Parallel Parking

The parallel parking process is performed by receiving environmental data from the vehicle's sensors and executing a predefined sequence of steering and movement commands.

The general parking process includes:

1. Detecting the available parking area
2. Positioning the vehicle beside the parking space
3. Moving backward with a calculated steering angle
4. Correcting the vehicle orientation
5. Positioning the vehicle inside the parking space
6. Stopping after reaching the desired position

## System Operation

The sensors continuously collect information about the surrounding environment.

The Arduino Mega processes the sensor data and determines the required movement commands.

The motors control the forward and backward motion of the vehicle, while the steering mechanism changes the direction of the front wheels.

During automatic parking, the controller executes a sequence of movements based on the detected distances and the predefined parking strategy.

## Hardware Components

- Arduino Mega
- Ackermann steering mechanism
- Environmental sensors
- DC motors
- Steering motor or servo motor
- Motor driver
- Vehicle chassis
- Power supply
- Wheels and mechanical components
- Electronic connections

## Technologies

- Arduino
- Embedded Systems
- C/C++
- Autonomous Vehicle Control
- Mobile Robotics
- Sensor-Based Navigation
- Motor Control
- Ackermann Steering Geometry
- Automatic Parking Algorithms

## Project Objectives

- Implement a practical vehicle steering mechanism
- Design a low-cost autonomous vehicle
- Demonstrate vehicle movement control in confined spaces
- Implement automatic parallel parking
- Integrate sensors, motors, and the control unit
- Study the behavior of Ackermann steering in autonomous vehicles

## Possible Future Improvements

- Implementation of closed-loop steering control
- Addition of PID controllers
- Use of wheel encoders
- Improvement of parking-space detection
- Path planning optimization
- Addition of obstacle avoidance
- Implementation of wireless monitoring
- Use of camera-based navigation
- Integration of machine vision
- Real-time vehicle position estimation
- Development of a mobile or web monitoring interface

## Academic Information

**Course Project**

**Supervisor:** Dr. Heidarali Talebi

## Author

**Aida Niknejad**  
Electrical Engineering – Control Engineering
