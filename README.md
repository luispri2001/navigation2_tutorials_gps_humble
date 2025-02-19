## Navigation2 Tutorials

[![Code Size](https://img.shields.io/github/languages/code-size/luispri2001/navigation2_tutorials_gps_humble.svg)](https://github.com/luispri2001/navigation2_tutorials_gps_humble) [![Last Commit](https://img.shields.io/github/last-commit/luispri2001/navigation2_tutorials_gps_humble.svg)](https://github.com/luispri2001/navigation2_tutorials_gps_humble/commits/main) [![GitHub issues](https://img.shields.io/github/issues/luispri2001/navigation2_tutorials_gps_humble)](https://github.com/luispri2001/navigation2_tutorials_gps_humble/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/luispri2001/navigation2_tutorials_gps_humble)](https://github.com/luispri2001/navigation2_tutorials_gps_humble/pulls) [![Contributors](https://img.shields.io/github/contributors/luispri2001/navigation2_tutorials_gps_humble.svg)](https://github.com/luispri2001/navigation2_tutorials_gps_humble/graphs/contributors)

## Tested systems and ROS2 distro
|systems|ROS2 distro|Build status|
|--|--|--|
|Ubuntu 22.04|humble|![Build Status](https://github.com/luispri2001/navigation2_tutorials_gps_humble/actions/workflows/main.yml/badge.svg?branch=Go2)

This repository is a fork of the original [navigation2_tutorials](https://github.com/ros-planning/navigation2_tutorials) repository, with modifications to ensure compatibility with ROS 2 Humble.

## Changes and Improvements
- Code adaptation to be compatible with the Humble version of ROS 2.

## Robot Compatibility: Unitree Go2 Quadruped

This particular branch has been modified to work specifically with the **Unitree Go2 quadruped robot**. The modifications include:

- Integration with the Unitree Go2’s hardware and sensors.
- Custom configurations and driver adaptations to ensure smooth operation within a ROS 2 Humble environment.
- Adjustments to the navigation stack to ensure optimal performance with the Unitree Go2's movement and control systems.

These modifications allow the robot to leverage GPS and other sensor data for navigation, making it suitable for autonomous operations.

## Usage
To clone this repository and compile it within a ROS 2 Humble workspace:

```sh
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
git clone https://github.com/luispri2001/navigation2_tutorials_gps_humble.git
cd ~/ros2_ws
colcon build --symlink-install
```

---

## Funding

This work has been funded under the following research projects:

### SELF-AIR Project

Supporting Extensive Livestock Farming with the use of Autonomous Intelligent Robots

<img src="https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/robotics_wolf_minimal.png" alt="SELF_AIR_logo" width="50%" height="50%">

Grant TED2021-132356B-I00 funded by MCIN/AEI/10.13039/501100011033 and by the “European Union NextGenerationEU/PRTR”

![SELF_AIR_EU eu_logo](https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/micin-financiadoUEnextgeneration-prtr-aei.png)

