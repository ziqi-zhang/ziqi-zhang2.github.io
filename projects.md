---
layout: default
---
# [](#header-1)Projects

## [](#header-2)Detect-SLAM: Making Object Detection and SLAM Mutually Beneficial

![]({{site.baseurl}}/assets/images/Detect_SLAM_framework.png)

Although significant progress has been made in SLAM and object detection in recent years, there are still a series of challenges for both tasks,e.g., SLAM in dynamic environments and detecting objects in complex environments. To address these challenges, we present a novel robotic vision system, which integrates SLAM with a deep neural network-based object detector to make the two functions mutually beneficial. The proposed system facilitates a robot to accomplish tasks reliably and efficiently in an unknown and dynamic environment. Experimental results show that compare to the state-of-the-art robotic vision systems, the proposed system has three advantages: i) it greatly improves the accuracy and robustness of SLAM in dynamic environments by removing unreliable features from moving objects leveraging the object detector, ii) it builds an instance-level semantic map of the environment in an online fashion using the synergy of the two functions for further semantic applications; and iii) it improves the object detector so that it can detect/recognize objects effectively under more challenging conditions such as unusual viewpoints, poor lighting condition, and motion blur, by leveraging the object map.

This work has been accepted by [WACV2018 (IEEE Winter Conf. on Applications of Computer Vision)](http://wacv18.uccs.us/)

## [](#header-2)A vision-based UAV system
This vision-based UAV system is capable of self-localization in indoor environment and conducting both dense and sparse reconstruction. It is mainly based on ROS, PX4 professional autopilot, mult-sensor fusion theory and ORB-SLAM system. Its sensors include a monocular camera, a optical flow sensor, a sonar sensor and IMU.

The sonar sensor and IMU is used to initializa the scale information for ORB-SLAM system and to conduct rough localization when ORB-SLAM system doesn't work. The optical flow sensor looks down to collect optical flow vision information, in case the visual slam system doesn't work. The monocular camera looks ahead to collect visual slam information.

The main part of localization system is ORB-SLAM, a versatile and accurate SLAM solution for Monocular, Stereo and RGB-D cameras. Multi-sensor fusion system consists of External Kalman Filter and some self-defined algorithms. The 3D reconstruction algorithm is DPPTAM (Dense Piecewise Planar Tracking and Mapping).

The sonar sensor and gyro is used to initializa the scale information for ORB-SLAM system and to conduct rough localization when ORB-SLAM system doesn't work. The optical flow sensor looks down to collect optical flow vision information, in case the visual slam system doesn't work. The monocular camera looks ahead to collect visual slam information. 

Experimental results have shown that this system is capable of hovering and navigating in indoor environment.



## [](#header-2)A multi-function smart car
![]({{site.baseurl}}/assets/images/Smart_car.png)
![]({{site.baseurl}}/assets/images/Reconstruction.png)
This multi-function smart car consists of three wheels. It is able to track people based on face features, search missing things, self-localize based on ORB-SLAM, 3D reconstruct, complete missions according human's voice order. 

This work represented Peking University to participate 5th College Students Innovation Exhibition of Beijing.
