# ROS 2 Robotics Learning Project

## Overview

This repository contains the robotics simulations and applications I developed while following the course "ROS 2 for Beginners Level 2 - TF | URDF | RViz | Gazebo".

The project covers robot modeling, visualization, simulation, and package organization using modern ROS 2 tools.

The repository includes both a differential drive mobile robot and a robotic arm simulation built using URDF/Xacro and tested in RViz and Gazebo.

---

## Features

- Differential drive mobile robot
- Robotic arm model
- URDF and Xacro robot descriptions
- Gazebo simulation
- RViz visualization
- ROS 2 launch files
- ros_gz_bridge configuration
- Custom Gazebo world

---

## Technologies Used

- ROS 2 Jazzy
- Gazebo
- RViz2
- URDF
- Xacro
- Python
- CMake
- XML Launch Files

---

## Repository Structure

```text
src/
├── robot_bringup/
│   ├── launch/
│   ├── config/
│   └── worlds/
│
└── udemy_robo1_description/
    ├── launch/
    ├── rviz/
    └── urdf/
```

---

## How to Build

```bash
colcon build
```

Source the workspace

```bash
source install/setup.bash
```

Launch the robot

```bash
ros2 launch robot_bringup first_robo_gazebo.launch.xml
```

---

## Learning Outcomes

Through this project I learned:

- ROS 2 package creation
- Workspace management
- Robot modeling with URDF/Xacro
- Coordinate frames and TF
- RViz visualization
- Gazebo simulation
- ROS-Gazebo integration
- Launch files
- Robot description organization

---

## Future Improvements

- Add robot controllers
- Integrate MoveIt 2
- Add Navigation2
- Add SLAM
- Integrate camera and perception
- Add autonomous behaviors

---

## Author

**Shubh Sanganeria**

B.Tech Robotics & Automation Engineering  
MIT World Peace University
