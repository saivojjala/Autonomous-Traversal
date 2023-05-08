# Autonomous Traversal of a 4 wheel bot
This repository contains the URDF for a 4 wheel Skid Steer Bot, and the codes for the autonomous traversal of the bot between GPS Coordinates while avoiding obstacles in its path. The code have been developed in Python using the Robot Operating System (ROS1 melodic).

## Sensors Used:
* GPS
* IMU
* 2D Lidar
* Ultrasonic Sensors

## YouTube Links:
### Autonomous Traversal between GPS Coordinates without obstacles
https://www.youtube.com/playlist?list=PLrUsVxhKCGEshQcjzMxDwWFORmM7c8YDE
### Autonomous Traversal between GPS Coordinates with obstacles
https://www.youtube.com/playlist?list=PLrUsVxhKCGEuAzTpqZYFIM7meoUGpfpIG


### An updated version of this repository is available at https://github.com/saivojjala/Distributed-Systems-Mini-Project. 
* The updates include a holonomic drive system and PID controller to accurately calculate velocity at a given instant in both the presence and abscence of obstacles. Incorporation of PID controller allows for a more robust and optimized traversal. 
