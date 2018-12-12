### Project Details

For this project, a "Reacher" environment is used. In this environment, a double-joined arm needs to move the blue "hand" to the green target. A reward of +0.1 is provided for each step that the agent's hand is inside the target. The goal for the agent is to maintain this position for as long as possible.

The state space consists of 33 variables that correspond to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with 4 numbers, corresponding to torque applicable to two joints. All actions should be clipped between [-1,1]. 

![ReacherGif](https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif)


### Getting Started

##### Instructions

1. Environment Setup

In order to ensure that your environment has all the necessary dependencies, follow the steps [here](https://github.com/udacity/deep-reinforcement-learning#dependencies)

2. Download the Environment

You will need to download the unity environment that matches your operating system below.

* [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
* [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
* [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
* [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

Unzip the the downloaded environment in the same location as the ipynb.