# Semi-Autonomous Emergency Drone Project

Welcome to the GitHub repository for the Semi-Autonomous Emergency Drone project, developed as part of the CEG 4912 - Computer Engineering Design Project I & II course at University of Ottawa. This repository serves as a central hub for project documentation, source code, and collaboration tools.

## Project Overview

### Team Members

- **Moise Baleke**

- **Zinah Al-Saadi**

- **Kenneth Sidibe**

- **Avneesh Chaudhary**

### Project Description

In this project, we are developing a semi-autonomous emergency drone designed for rapid response and effective incident monitoring. The drone will be dispatched to emergency scenes upon activation and will assess the situation while mapping the area using a 3D scanner. This critical information will be relayed to the rescue team before their arrival, enhancing response time and monitoring capabilities for large-scale incidents.

## Repository Contents

- **Documentation:** Contains project-related documents, including project plans, design specifications, testing reports, and presentations.

- **Code:** Holds the source code for the drone's software and control systems.

- **Issues:** Utilize the GitHub Issues feature for tracking and managing project tasks, assignments, and discussions.

- **Wiki:** The repository's Wiki is a resource for in-depth documentation, tutorials, and knowledge sharing.

## Key Project Components

### Hardware

- **CPU Component:** Utilizing Raspberry Pi or Xilinx Kria kv260.
- **Flight Controller:** Pixhaux flight controller.
- **Sensors and Actuators:** Includes LIDAR, GPS, speakers, microphones, 4 motors, cameras.
- **Power Supply:** Raspberry Pi 4 15W USB-C power supply and Xilinx Kria 36W power supply.

### Software

- **Operating System:** Raspberry Pi OS (Debian) for compatibility.
- **Communication Stack:** Implementation of MQTT for real-time communication.
- **Programming Language:** Python for its extensive libraries (e.g., OpenCV, GPIO, TensorFlow) and Raspberry Pi hardware integration.
- **Database:** MongoDB.
- **Interface:** A web-based interface accessible via a link featuring a login.

### Architecture

The project architecture is divided into several layers:

- **User Interface Layer:** Provides a user-friendly interface for mission planning, monitoring, and control.

- **Control and Communication Layer:** Handles data transmission, commands, and telemetry data between the control center and the drone. Ensures real-time communication and security.

- **Mission Planning and Execution Layer:** Manages mission planning, task assignment, and execution, including autonomous navigation and obstacle avoidance.

- **Perception and Sensing Layer:** Contains sensors and perception systems for environmental awareness, including GPS, cameras, lidar, and more.

- **Control and Decision-Making Layer:** Implements control algorithms and decision-making logic based on sensor data and predefined protocols.

- **Hardware Layer:** Comprises physical drone hardware, including the quadcopter frame, motors, propellers, battery system, onboard computer, and payload attachment mechanisms.

- **Payload and Equipment Layer:** Manages the attachment and release of payloads or emergency supplies, ensuring secure delivery.

- **Data Processing and Analysis Layer:** Handles data processing, logging, and integration with GIS for map-based navigation.

- **Testing and Validation Layer:** Supports testing at various stages of development, validating the drone's performance in different conditions and emergency scenarios.

- **Safety and Redundancy Layer:** Implements safety mechanisms, fail-safes, and redundancy for critical situations.

## Project Roadmap

For a detailed project timeline and tasks breakdown, please refer to the [Gantt Chart](link-to-gantt-chart) and [Work-Breakdown Structure](link-to-wbs) in the repository.

## How to Get Involved

If you are a student enrolled in CEG 4912, please follow the course syllabus and instructions provided by Dr. Ionescu for specific project requirements and expectations.

If you have any questions or wish to contribute to the project, please reach out to the team manager, Moise Baleke, at [mbale067@uottawa.ca](mailto:mbale067@uottawa.ca).

We appreciate your interest in our Semi-Autonomous Emergency Drone project and look forward to a successful collaboration!
