Object Detection and Robotic Arm Movement using ROS and MoveIt
This project integrates object detection with robotic arm movement using ROS (Robot Operating System) and MoveIt. It utilizes a Kinova Gen3 robotic arm and Darknet-ROS for object detection, allowing the robotic arm to move to the coordinates of detected objects.
Table of Contents
  Introduction
  Features
  Hardware Requirements
  Software Requirements
  Installation
  Usage
  Future Work
  Contributing
  License
Introduction
  Robotic automation is transforming industries, enhancing efficiency and precision. This project combines vision-based object detection with robotic arm manipulation, creating a versatile system that can be used in various   applications such as manufacturing, healthcare, and service robotics.

Features
 Real-time object detection using Darknet-ROS. 3D coordinate computation of detected objects. Transformation of coordinates from camera frame to robot base frame. Motion planning and execution using MoveIt. Stability check for object coordinates before executing movement.
Hardware Requirements
Kinova Gen3 vision-based 7 DOF robotic arm.
Depth camera (e.g., Intel RealSense).
Software Requirements
ROS-Noetic
ROS-Kortex
ROS-Vision modules
Darknet-ROS
MoveIt

