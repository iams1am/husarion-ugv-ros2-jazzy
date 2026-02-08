# Husarion UGV ROS 2 Jazzy Simulation Workspace

This repository contains a ROS 2 Jazzy workspace for simulating
Husarion UGV platforms (Panther/Lynx) using Gazebo Harmonic.

<img width="1948" height="998" alt="Screenshot from 2026-02-09 03-22-35" src="https://github.com/user-attachments/assets/e675d369-04dd-4666-99b7-07f54d84e671" />
<img width="1920" height="1080" alt="Screenshot from 2026-02-09 03-57-06" src="https://github.com/user-attachments/assets/6d2825da-e2a6-4d77-a7aa-f71672ceff20" />
<img width="1920" height="1080" alt="Screenshot from 2026-02-09 03-56-55" src="https://github.com/user-attachments/assets/3616fa69-f547-4e4f-b9c6-2acd0fca41c8" />




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
```bash
source /opt/ros/$ROS_DISTRO/setup.bash
source ~/husarion_ws/install/setup.bash
ros2 launch husarion_ugv_gazebo simulation.launch.py use_sim:=True robot_model:=panther 
```
