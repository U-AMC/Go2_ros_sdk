# Go2_ros_sdk
ROS(noetic) publisher for Go2 Unitree Robot, requires 20.04 ubuntu


## 1. Features
Based on Unitree_SDK2(Go2) package, ROS noetic, the following package publishes Go2 LiDAR, and **Go2 HighState (HighState + LowState API)** to be compatible with **Go1 HighState** format.
The purpose of this package is to make it more easy and compatible with estimators and SLAM system.

<div align="center"><img src="figures/image.png" width=90% /></div>

## Prerequisites
**[Unitree_legged_sdk](https://github.com/unitreerobotics/unitree_legged_sdk)**

**[Unitree_sdk2](https://github.com/unitreerobotics/unitree_sdk2)**

**[Unitree_legged_msgs](https://github.com/unitreerobotics/unitree_ros_to_real.git) (included in the repository)**

ROS Noetic(Ubuntu 20.04)

LCM

-----------------------------
The following package will also be a part of upcoming dataset, [DiTer++](https://github.com/sparolab/DiTer-plusplus) which extensively integrates every proprioceptive and exteroceptive measurements for single / multi-robot research.
