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

Download environment for your system into this repository root

1. Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip

Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip

Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip

Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip

2. Unzip (or decompress) the archive

3. Run the requirements.txt in the shell: pip install -r requirements.txt

# Executing the code:

The code can be executed directly in the jupyter notebook running all the cells in order from top till the "Main" cell.
After the "Main" cell there are some additional cells if one wants to modify DDPG and turn it into a naive version of D4PG. In order to do so follow the instruction into the notebook.
