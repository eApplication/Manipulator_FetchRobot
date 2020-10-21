<<<<<<< HEAD
# Simulation of Visual Servoing on Fetch Robot in Gazebo Environment

=======
# Simulation of Visual Servoing Algorithm on Fetch Robot in Gazebo

|![image](https://github.com/JiadingWen/Manipulator_FetchRobot/blob/master/img/ScreenShot1.gif)|![image](https://github.com/JiadingWen/Manipulator_FetchRobot/blob/master/img/ScreenShot2.gif)|
| - | :-: |

<p align="center">Find cube, Pick cube</p>

***
## Introduction

To be continue...

## Prerequisites
Before running code, make sure you have following software installed in **Ubuntu 16.04** :

* [Robot Operating System (ROS)](https://www.ros.org/): a set of software libraries and tools that help you build robot applications. You can click the link to find out how to install ROS. 

* [ros-kinetic-fetch-gazebo](http://ros.org/wiki/fetch_gazebo): a gazebo package for Fetch robot. It help us simulating Fetch robot in Gazebo. Use commend `sudo apt install ros-kinetic-fetch-gazebo` to install this package.



All the codes have **Only** been tested on 
* Ubuntu 16.04 LTS 
* ROS kinetic
* Gazebo7
* ros-kinetic-fetch-gazebo 0.8.2

There is no guarantee that the codes have good compatibility in other versions. 


## Usage

Run following two commends in terminal:

`roslaunch fetch_gazebo_visualservoing environment.launch` 
#Create Fetch Robot in Gazebo and prepare robot maipulator.

`roslaunch fetch_gazebo_visualservoing simulation.launch` #Using head camera to find the cube and pick it.


***
Enjoy playing robot!!

:star: Star us on GitHub — it helps! 
>>>>>>> demo
