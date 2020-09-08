# Actor_Critc_for_Udacity
Solving a robot arm environment for the Udacity Deep Reinforcement Learning Course.

TASK:

In this Project we are going to solve the "reacher Unity environment".

The environment consists of a double-jointed arm that can move to target locations. A reward of +0.1 is
provided for each step that the agent's hand is in the goal location (notice in the new version of the environment the rewards 
were smaller and more sparse. Therefore in the main function of the Jupyter notebook there are few lines of code used
to renormalize the rewards.).

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular 
velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two 
joints.

The environment is considered solved if we get an average reward of +30 along 100 consecutive episodes.

DEPENDENCIES AND LIBRARIES TO INSTALL:

The libraries to install, assuming python is present on your machine are

1. Open Ai gym. 
A minimal installation can be obtained running "pip install gym" on your terminal.
2. Pytorch
An installation can be obtained running "pip3 install torch torchvision"
3. Unity Environments
for which one can follow the link https://secretlab.institute/2019/07/11/installing-unity-ml-agents/
4. Numpy if it is not already installed


