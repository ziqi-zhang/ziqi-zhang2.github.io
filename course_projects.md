---
layout: default
---
# [](#header-1)Course Projects
## [](#header-2)A Multi-robot SLAM System
This is a multi-robot SLAM system based on RobotSDK, Qt and C++. I use Tcp packages of Qt to establish a communication system between different smart cars and control center. Through this system, control center can draw a 2D occupancy grid map based on location and Lidar data collected by each car.

## [](#header-2)A Parallel Implementation of DAG Traversal Problem
We implement a parallel solution for the DAG Traversal Problem respectively based on CUDA and OpenMP. For the implementation based on OpenMP, we concurrently optimize the topological sort process. For the implementation based on CUDA, we change the state-of-the-art breadth first search algorithm to optimize the topological sort process and the node update process.

## [](#header-2)RISC-V Simulator
We implement a RISC-V simulator based on C. This simulator can resolve ELF files based on RISC-V instruction set architecture.

This simulator can execute RV32I and RV64I base imteger instruction set, "M" standard extension for integer multiplication and division and "F" standaed extension for single-precition floating-point. It consists of registers, a memeory,  a cache and so on. The cache can support different replace strategies.

## [](#header-2)An AQI Detector APP
We implement a AQI detector application based on Swift and python. User can take a photo towards the sky and upload this photo to the server. Server analyses the photo and gives an estimated AQI number in that environment.

We use Grab-Cut algorithm to segment sky from foreground, then feed the sky part into a classifier. To train the classifier, we collected hundreds of images taken at several places in different air condition.

## [](#header-2)Implementing a Calculator and a Timer on FPGA
I use Verilog to implement a calculator and a timer on FPGA. The implementation includes a display part, a counting part and a timing part. The calculator is able to do add, minus and multiple operations.

## [](#header-2)A Multi-functional Dictionary
We implement a multi-functional dictionary based on Java. The dictionary has a beautiful interface and can search words online, search words in local dataset and help users to memorize new words based on The Ebbinghaus Forgetting Curve.

## [](#header-2)A Mine Sweeper Game
I implement a mine sweeper game based on C++. It has the function of loading and saving games, ranking list and adjusting degree of difficulty.
