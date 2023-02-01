# Point-LIO
## Point-LIO: Robust High-Bandwidth Lidar-Inertial Odometry

## 1. Introduction
**ImMesh** is a novel LiDAR(-inertial) odometry and meshing framework, which takes advantage of input of LiDAR data, achieving the goal of **simultaneous localization and meshing** in real-time. ImMesh comprises four tightly-coupled modules: receiver, localization, meshing, and broadcaster. The localization module utilizes the prepossessed sensor data from the receiver, estimates the sensor pose online by registering LiDAR scans to maps, and dynamically grows the map. Then, our meshing module takes the registered LiDAR scan for **incrementally reconstructing the triangle mesh on the fly**. Finally, the real-time odometry, map, and mesh are published via our broadcaster.

## **Date of code release**
Our paper is currently under review, and **the code of Point-LIO will be released as our work is accepted**.

### 1.1 Our paper

### 1.2 Our accompanying videos
Our **accompanying videos** are now available on **YouTube** <sup>[1](https://youtu.be/oS83xUs42Uw)</sup>.

## 2. What can Point-LIO do?
### 2.1 Simultaneous LiDAR localization and mapping (SLAM) without motion distortion

### 2.2 Produce high odometry output frequence and high bandwidth

### 2.3 SLAM with aggressive motions even the IMU is saturated

## 3. Contact us
If you have any questions about this work, please feel free to contact me <hdj65822ATconnect.hku.hk> and Dr. Fu Zhang <fuzhangAThku.hk> via email.
