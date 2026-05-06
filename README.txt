Project Introduction:

Sir, this project is a reproduction and continuation of the autonomous robot project that I previously worked on during my internship at the Research Center and presented during the previous project presentation session.

The objective of this work is to reproduce and further develop the same intelligent navigation system using ROS 2 and NVIDIA Jetson.

This project is an autonomous mobile robot developed using ROS 2 and NVIDIA Jetson.
The robot is capable of autonomous navigation and obstacle avoidance without direct control from a computer or joystick.

The robot uses a LiDAR sensor to:
- measure distances,
- create maps of the environment,
- and perform navigation using generated maps.

The project also uses SLAM (Simultaneous Localization and Mapping) to:
- localize the robot in the environment,
- generate real-time maps,
- and build the map used for navigation.

In addition, the Nav2 (Navigation2) stack is used to:
- calculate trajectories,
- plan paths,
- and navigate autonomously from one point to another while avoiding obstacles.

The robot also uses YOLO object detection to identify:
- people,
- cars,
- and different obstacles in real time,
in order to improve navigation safety and intelligent decision-making.

The robot is controlled by an NVIDIA Jetson board acting as the robot’s onboard computer and “brain”.
Unlike traditional systems controlled directly by a PC or joystick, this robot processes data and makes decisions autonomously using the Jetson platform.
