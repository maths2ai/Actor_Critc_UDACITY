# Continuous Control for Udacity
Solving a robot arm environment for the Udacity Deep Reinforcement Learning Course.

## TASK:

In this Project we are going to solve the "reacher Unity environment".

The environment consists of a double-jointed arm that can move to target locations. A reward of +0.1 is
provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular 
velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two 
joints.

The environment is considered solved if we get an average reward of +30 along 100 consecutive episodes.

## Installation

Install deep reinforcement learning repository

1. Clone deep reinforcement learning repository https://github.com/udacity/deep-reinforcement-learning
2. Fallow the instructions to install necessary dependencies https://github.com/udacity/deep-reinforcement-learning#dependencies

## Download the Unity Environment

Download environment for your system into this repository root

1. Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip

Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip

Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip

Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip

2. Unzip (or decompress) the archive

## Run the project

Start the jupyter server

Open the Continuous_Control.ipynb notebook

Change the kernel to drlnd 

Run cells from top to bottom in the Jupyter Notebook, till the Prio Buffer cell. If you want to run the DDPG with the add of a prioritized experience buffer follow the instructions in the markdowns in the Jupyter Notebook.
