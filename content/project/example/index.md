---
title: Dataset for SLAM Algorithms in Adverse Conditions
summary: A brief introduction to my works in this project
tags:
  - SLAM
date: '2016-04-27T00:00:00Z'



image:
  caption: Demo photo from Kitti Dataset
  focal_point: Smart

links:
  - icon: gitlab
    icon_pack: fab
    name: Follow
    url: https://gitlab.eecs.umich.edu/umfordav/thermal_dataset/-/tree/master
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

---
The overall goal of the project is to develop novel deep learning algorithms on next generation sensors to perform SLAM in a variety of weather and lighting conditions. The project includes collecting ground truth data from a multi-sensor rig to aid development and testing of SLAM algorithms. These multi-sensor rigs will be mounted on a UGV and a Ford Fusion AV platform. My responsibility in the project is to help set up the multi-sensor rig, collect data for the benchmarking dataset, and evaluate the quality of the dataset by experimenting on several existing SLAM pipelines before applying our own algorithms. In more details, my contributions involve: 

1. help to test, debug and deploy the prototype of the multi-sensor rig to validate the methodology. The platform includes Blackfly cameras, event cameras, duro-inertial units (including a lidar antenna and an IMU unit);
2. test the calibration method between the multiple sensors and write up the documentation. The calibration is carried out between lidar units, cameras and gnss-ins units;
3. help to complete post-processing tasks to generate the ground-truth trajectories from the gnss-ins unit and write up the documentation;
4. carry out some initial tests on the dataset using existing SLAM algorithms (including ORB-SLAM3 and DSM) and evaluating the performance;
5. help to develop deep-learning algorithms to de-blur the visual images using data from thermal cameras and event cameras simultaneously;
