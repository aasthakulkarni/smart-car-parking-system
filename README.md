
# Smart Car Parking System Using IoT

## Overview

The Smart Car Parking System is an IoT-based project designed to monitor parking slot availability in real time. The system uses IR sensors to detect vehicle occupancy and displays parking status on an LCD screen. A servo motor automatically controls the entry and exit gate based on slot availability, helping reduce traffic congestion and parking search time.

## Features

* Real-time parking slot monitoring
* Automatic gate control using servo motor
* LCD display for slot availability
* Vehicle entry and exit detection
* Parking occupancy tracking
* Low-cost and efficient solution
* IoT-based parking management

## Hardware Components

* Arduino UNO
* NodeMCU
* IR Sensors
* Servo Motor
* LCD Display with I2C Module
* Breadboard
* Jumper Wires
* Power Supply

## Software Requirements

* Arduino IDE
* Embedded C Programming
* NodeMCU Libraries
* LCD I2C Library
* Servo Motor Library

## System Architecture

1. IR sensors detect vehicle presence in parking slots.
2. Entry sensor checks incoming vehicles.
3. Arduino processes sensor data.
4. Servo motor opens the gate if slots are available.
5. LCD displays slot status as Empty or Full.
6. Exit sensor updates parking availability when vehicles leave.
7. Parking information is updated in real time.

## Working

* When a vehicle arrives, the entry sensor detects it.
* The system checks available parking slots.
* If a slot is available, the gate opens automatically.
* Once the vehicle occupies a slot, the status changes to Full.
* The LCD continuously displays slot information.
* When a vehicle exits, the slot becomes available again and the gate opens automatically.

## Project Objectives

* Automate parking management.
* Reduce vehicle search time.
* Improve parking space utilization.
* Minimize traffic congestion.
* Provide real-time parking information.

## Results

* Successfully detected parking slot occupancy.
* Automated vehicle entry and exit management.
* Improved parking efficiency.
* Reduced manual monitoring requirements.
* Demonstrated real-time IoT sensor integration.

## Future Enhancements

* Mobile application integration.
* Cloud-based monitoring dashboard.
* Online slot booking.
* RFID-based vehicle authentication.
* License plate recognition.
* Real-time notifications.

## Technologies Used

* IoT
* Arduino UNO
* NodeMCU
* Embedded C
* IR Sensors
* Servo Motor
* LCD Display

