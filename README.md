# Husarion UGV ROS 2 Jazzy Simulation Workspace

This repository contains a ROS 2 Jazzy workspace for simulating
Husarion UGV platforms (Panther/Lynx) using Gazebo Harmonic.

## System
- Ubuntu 24.04 LTS
- ROS 2 Jazzy
- Gazebo Harmonic

## Build
```bash
cd husarion_ws
colcon build
source install/setup.bash
```

# RUN Simulation
```ros2 launch husarion_ugv_gazebo simulation.launch.py use_sim:=True robot_model:=panther 
