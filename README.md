# SOFAR_Object_Following_Robot
This is the final Assignment of the our course Software Architectures for Robotics (SofAR) in which we are asked to build a simulation with ROS in which a robot follows
a moving target (e.g., a person or another robot) at a fixed distance.

## method was Implemented in this case
* Using OpenCV (ROS)

This project aims to make the robot follow a particular object while also keeping a minimum safe distance from it.

The software stacks implemented in this project are ROS and Python. We also made use of OpenCV for the object detection part.

We aim to further expand this project and make it a person-follower.

## Clone the Object Follower package

Now go ahead and clone this repository inside the "src" folder of the catkin workspace you just created by executing the command given below in your terminal.

Now launch the the file by using the following command in terminal

roslaunch bridge_example gazeebo_ex.launch
![image](https://user-images.githubusercontent.com/105802251/211953307-90abc088-8a61-4256-bba6-f46542aecd1b.png)


Here after launching the package, you will see the two windows, In one you will see two robots one(Robot_1) moves and other(Robot_2) looking for the robot_1 by using CV detecting operation when in seach the defined colour it lock it and then it will try to allign itself in center of that colour to keep detecting to follows it and in sencond window you will see the camrea view of the robot_2 to visualize the detection process. 
