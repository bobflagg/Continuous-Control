# Continuous-Control
My submission for Project 3 from [Udacity's Deep Reinforcement Learning Nanodegree Program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).  

## Project Details

In the [reacher environment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) for the Continuous Control Project a double-jointed arm can move to target locations. 
A reward of +0.1 is provided for each step that the agent's hand is in the goal location. 
Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular 
velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two 
joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.

## Getting Started

If you would like to run this code locally follow the instructions below.

1. Set up your Python environment as described the dependencies section of the [readme](https://github.com/udacity/deep-reinforcement-learning) from the [Deep Reinforcement Learning Nanodegree program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893). 
2. Clone this repository.
3. Create a directory called "data" at the root of the cloned repository.
4. Select the environment that matches your operating system from the list below:
    - [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    - [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    - [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    - [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
5. Place the file in the data folder you created above.
6. Unzip (or decompress) the file.

## Instructions

You can train an agent to solve the [reacher environment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) by executing the cells in the 
[Continuous Control](https://nbviewer.jupyter.org/github/bobflagg/Continuous-Control/blob/master/01-Continuous-Control-with-DDPG.ipynb) notebook.  The code in that notebook is self-contained except for a few simple utility functions, which are saved in the Python module [util.py](https://github.com/bobflagg/Continuous-Control/blob/master/util.py).
