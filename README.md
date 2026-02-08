# Husarion UGV ROS 2 Jazzy Simulation Workspace

This repository contains a ROS 2 Jazzy workspace for simulating
Husarion UGV platforms (Panther/Lynx) using Gazebo Harmonic.

<img width="1922" height="963" alt="Screenshot from 2026-02-09 03-22-35" src="https://github.com/user-attachments/assets/a90692ad-2839-4d75-bb5d-93f88a7ffe1c" />
<img width="1920" height="971" alt="Screenshot from 2026-02-09 03-57-06" src="https://github.com/user-attachments/assets/20961c34-806b-4f3d-9bf4-da13fa67e201" />
<img width="1920" height="977" alt="Screenshot from 2026-02-09 03-56-55" src="https://github.com/user-attachments/assets/304e3786-99e8-4c3f-85ae-8c0a89493cd2" />




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
