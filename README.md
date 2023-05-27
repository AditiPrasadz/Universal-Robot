# Universal-Robot
Universal Robot UR10 e-series

This repository provides an guide on my work done with integrating the Universal Robot UR10 e-series robotic arm with various technologies such as Profinet compatible devices such as PLC and ROS system. Due to NDA from company, the repository only brief on utilizing the Profinet communication protocol for seamless communication with PLC, leveraging the power of ROS-Melodic for control and visualization through RVIZ, and incorporating OPC-UA Information Modelling using Siemens SiOME.

## Table of Contents
- Introduction
- Profinet Communication Protocol
- ROS-Melodic Implementation
- RVIZ Visualization
- OPC-UA Information Modelling using Siemens SiOME
- Installation
- Usage
- Contributions

## Introduction
The Universal Robot UR10 e-series is a highly versatile robotic arm designed for industrial applications. This repository aims to provide a comprehensive guide to my project on the UR10 e-series with ROS system to enhance its capabilities.

## Profinet Communication Protocol
Profinet(Industrial Ethernet protocol) enables real-time communication and data exchange between industrial automation systems. By implementing the Profinet communication protocol, I establish a seamless connection between the UR10 e-series and PLC.

## ROS-Melodic Implementation
ROS (Robot Operating System) is a flexible framework for writing robot software. ROS-Melodic, the version targeted in this project, provides a stable and widely used environment for controlling and coordinating the UR10 e-series robotic arm. It offered various tools and libraries to facilitate development using python programming, communication using ethernet ip, and visualization of robotic systems in gazebo & Rviz.

## RVIZ Visualization
With RVIZ (3D visualization tool) I was able to monitor and interact with the UR10 e-series robot arm in a graphical interface. This feature allowed me to observe the robot's movements, visualize sensor data, and perform simulations to validate control algorithms.

## OPC-UA Information Modelling using Siemens SiOME
OPC-UA (Unified Architecture): Standard communication protocol widely used in industrial automation.

By implementing OPC-UA Information Modelling using Siemens SiOME, I created structured representation of the UR10 e-series tags, enabling seamless integration with PLC via TIA -Portal. This approach enables monitore the conformity of the robotic arm.


## Contributions
Independant work! If you find any issues or have ideas to enhance the functionality, please open an issue or submit a pull
