# Robotic-arm

In this project we deal with the design and control of a robotic arm that can move to desired positions. The robot arm consists of 6 revolute joints hence 6DOF. 

---

### Table of Contents

- [Installation](#installation)
- [Technologies](#technologies)
- [How To Use](#how-to-use)
- [Author Info](#author-info)

---

## Installation

- Use these commands to install ROS Melodic on Ubuntu 18.04: 
    > sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
    > sudo apt install curl
    > curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
    > sudo apt update
    > sudo apt install ros-melodic-desktop-full

- Install git
    > apt-get install git

- Creating catkin workspace: 
    > source /opt/ros/melodic/setup.bash
    > mkdir -p ~/catkin_ws/src
    > cd ~/catkin_ws/
    > catkin_make
    > source devel/setup.bash
 
 - Cloning the github repository
    > cd ~/catkin_ws/src/
    > git clone https://github.com/H-P-Jeevan/Robotic-arm.git

 - Installing packages
    > sudo apt-get install ros-melodic-moveit
 
---

## Technologies

- ROS
- Moveit

---

## How To Use

#### Running simulation
  > roslaunch myrobt_moveit_config demo.launch

---

## Author Info

- H P Jeevan https://www.linkedin.com/in/h-p-jeevan-08607a1a8
