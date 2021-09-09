# RoboND-RTABMAP-SLAM-Project
3D mapping with RTAB-MAP  

Udacity Robotics Software Engineer Nanodegree Project 4 

This project creates a 2D occupancy grid and 3D octomap from a Gazebo simulated environment with the RTAB-Map package (http://wiki.ros.org/rtabmap_ros).

## Installation

  Follow the RTAB-Map installation instructions from http://wiki.ros.org/rtabmap_ros
  
  git clone https://github.com/AlmasShintemirov/RoboND-RTAB-Map-SLAM-Project.git to your "catkin_ws"/src folder
  
  git clone git clone https://github.com/ros-teleop/teleop_twist_keyboard to your "catkin_ws"/src folder
  
  cd ..
  
  catkin_make
  
  source devel/setup.bash

## Running

roslaunch my_robot_slam world.launch

roslaunch my_robot_slam teleop.launch

roslaunch my_robot_slam mapping.launch


Recorded database can opened and viewed using rtabmap-databaseViewer:

rtabmap-databaseViewer ~/.ros/rtabmap.db

![Screenshot from 2021-09-07 21-43-00](https://user-images.githubusercontent.com/13367696/132380884-50dd08e3-18b3-418c-9d1e-612b3ce9363e.png)

