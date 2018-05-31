
# RoboND-DeepRL-Project-Solution

This is a solution of the [Deep RL Arm Manipulation](https://github.com/udacity/RoboND-DeepRL-Project) project as part of the Robotics Nanodegree. The goal of the project is to set up and optimize a reinforcement learning framework. A Deep Q-Network learns to control a robotic arm in a simulated Gazebo environment. The reinforcement learning agent is given the task of touching a target object.

The implementations of the tasks can be found in the file [`ArmPlugin.cpp`](gazebo/ArmPlugin.cpp). The writeup report can be found [here](writeup/writeup_deep_rl.pdf).

## Setup
This project runs on Ubuntu Linux with Gazebo installed. Follow the instructions in the [Deep RL Arm Manipulation](https://github.com/udacity/RoboND-DeepRL-Project) project.

## Usage
To launch the project environment, change directories to the `bin` folder and run

``` bash
$ ./gazebo-arm.sh
```
This starts Gazebo and runs the training script.

<img src="https://github.com/dusty-nv/jetson-reinforcement/raw/master/docs/images/gazebo_arm.jpg">
