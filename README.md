
# Jarrett Philips - Portfolio

## Table of Contents
1. [Project Marion - Gravity Offload System](##Project_Marion_-_Gravity_Offload_System)



## Project Marion - Gravity Offload System

![](marion.png)

In order to ensure reliability in orbit, solar arrays must be precisely testing is conducted on the ground. This requires the offload of gravitational forces while minimizing any forces imposed by the testing fixture itself.As our senior project at CU Boulder's Design Center Colorado, we partnered with BallAerospace to develop a new test fixture. This project is a solution provides an active, scalable, and reconfigurable apparatus to support ground testing for a wide range of solar array sizes and variable deployment architectures.The prototype implements a computer vision control system to autonomously track the path of each individual solar panel in the array. The active, two-axis gantry system positions itself over the attachment point suspending each solar panel, minimizing lateral forces during testing. I was the systems engineer and lead software engineer, responsible for the planning and creation of a vast majority of the codebase, including the Robotic OperatingSystem (ROS) framework, computer vision systems (Python), reactive and predictive motion path generation (Python), motor drivers (C++), as well as system administration and networking. Its source code remains Ball's IP, but our white paper is available for everyone to read!

## Independent Proximity Sensor

![](ips.jpg)

A custom built sensor used to generate point clouds of an environment. The handheld sensor has numerous infrared distance sensors mounted. Tracking orientation enables the user to roll and move the sensor with their hand to scan the environment while maintaining accurate data measurements. This freedom on motion also allows a motor-less design, instead relying on intelligent software to track the infrared sensors orientation through an IMU chip and map the data accordingly. Once the sensor data is gathered, it is then be transmitted (Arduino / C++) to an external computer which stores and renders the produced point cloud in read time (Python). A more detailed report is also available for more detail on the mathematics.

## Self Landing Drone
<img align="left" width="50%" src="test.jpg"> A quadcopter program that can identify, locate, approach, and land on a moving platform of unknown trajectory. A robot (Arduino / C++) is used to move the landing pad in a randomized path. The system is coordinated through ROS running on a central computer. I was responsible for the computer vision code (Python) that locates the pad within the camera's feed and determines its relative position (in meters) to the drone.

## Journaling Application
![](chronicle.png)

Built from scratch using Java Swing, this application allows reading and writing of journal entries stored in a universal format for easy manipulation in or out of the program. It supports photos and a ranking system which alters the color of the presented entry.

## Drill Powered Bike
<img align="right" width="40%" src="bike.png">
A custom built bicycle driven by a drill made to complete a hill course. The process included design, CAD work, drawing creation, and manufacturing. I was responsible for systems integration and most manufacturing, including various machining tasks and welding.

<br />
<br />
<br />
<br />
<br />
<br />


## BASIC 3D GRAPHICS ENGINE
<img align="left" width="40%" src="graphics.png">
A basic rendering engine created from scratch in Java. It implements basic 3D objects from data files provided to it. It using only a library to draw polygons, so all translational, camera, and rendering calculations are custom made. It features clipping, movement, rotation, and camera movement. A small UI allows the user to switch between perspective and parallel rendering.

<br />
<br />
<br />
<br />

## Edge Detection
![](edge_detection.png)
Run from the command line, this C++ application takes a photo as an input, and generates a new image, marking all of the edges identified.
