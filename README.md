# Continuous-Control
My submission for Project 2 from [Udacity's Deep Reinforcement Learning Nanodegree Program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).  

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

I've organized the code into three Python modules, which contain code common to the various solutions, and four Jupyter notebooks containing increasingly more efficient solutions.

1. **Python Modules**
    - [model.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/model.py): implements an actor policy model as a simple neural network.
    - [agent.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/dqn_agent.py): defines an abstract RL agent for deep Q-learning which will be subclassed in the specific solutions.
    - [trainer.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/trainer.py): implements the method used to train the agents.
2. **Jupyter Notebooks**
    - [Deep Q-Learning for Navigation](https://nbviewer.jupyter.org/github/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/01-Deep-Q-Learning-for-Navigation.ipynb)
    - [Double Deep Q-Learning for Navigation](https://nbviewer.jupyter.org/github/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/02-Double-Deep-Q-Learning-for-Navigation.ipynb)

You can train an agent to solve the Navigation Environment by executing the cells in the corresponding notebooks.

## Additional Resources

- [Deep Communicating Agents for Abstractive Summarization](http://www.aclweb.org/anthology/N18-1150)
- [RL-Adventure-2: Policy Gradients](https://github.com/higgsfield/RL-Adventure-2)
- [Implementation of Soft Actor Critic](https://github.com/vaishak2future/sac)
- [Soft Actor-Critic Demystified](https://towardsdatascience.com/soft-actor-critic-demystified-b8427df61665)
- [Reinforcement Learning: From Zero to State of the Art with Pytorch 4](https://hk.saowen.com/a/4c888d90bd87479766f85a5dafb77559a29cf562053b9f5d0ae2367a46f3c02a)
- [PyTorch implementation of Proximal Policy Optimization](https://github.com/lnpalmer/PPO)
- [Open AI: Proximal Policy Optimization](https://blog.openai.com/openai-baselines-ppo/)
- [Policy Gradient Algorithms](https://lilianweng.github.io/lil-log/2018/04/08/policy-gradient-algorithms.html)
- [Deep Reinforcement Learning for Natural Language Processing!](https://www.fortia.fr/2018/08/01/deep-reinforcement-learning-natural-language-processing/?lang=en)
- [Implementation of the Deep Deterministic Policy Gradient (DDPG) using PyTorch](https://github.com/ghliu/pytorch-ddpg)
- [PyTorch implementation of DDPG algorithm for continuous action reinforcement learning problem.](https://github.com/vy007vikas/PyTorch-ActorCriticRL)
- [In Progress : State of the art Distributed Distributional Deep Deterministic Policy Gradient algorithm implementation in pytorch](https://github.com/ajgupta93/d4pg-pytorch)
- [Self Learning AI-Agents Part II: Deep Q-Learning](https://towardsdatascience.com/self-learning-ai-agents-part-ii-deep-q-learning-b5ac60c3f47)

DDPG (Actor-Critic) Reinforcement Learning using PyTorch and Unity ML-Agents

In Progress : State of the art Distributed Distributional Deep Deterministic Policy Gradient algorithm implementation in pytorch.
https://github.com/ajgupta93/d4pg-pytorch
