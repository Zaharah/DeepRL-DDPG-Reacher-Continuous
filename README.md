# Continuous Control with DDPG

## Introduction
Implementation of DDPG algorithms to solve the contiunous action space of Unity Reacher Environment :rocket:.
Random Agent            |  Trained Agent
:----------------------:|:-------------------------:
![](https://github.com/Zaharah/DeepRL-DDPG-Reacher-Continuous/blob/master/real-p2.gif)  |  ![](https://github.com/Zaharah/DeepRL-DDPG-Reacher-Continuous/blob/master/trained-p2.gif)

 - *Agent*: A double-jointed arm that can move to targer location. 
 - *Environment*: In the Reacher environment (:earth_asia:), the target location is a moving ball rotating around the agent. 
 - *Action size*: The action size is four with continuous nature, where a single action can take any value between -1 to 1. 
 - *Observation space*: The state space consists of 33 variables corresponding to position, rotation, and angular velocities of the arm. 
 - *Rewards*: There is +1 reward(:+1:) of each step the agent’s hand is at target location. 
 - *Goal*: The environment is considered solved (:star:) when an agent accumulates an average reward of +30 for :100: consecutive episodes. 
 - *Apporach*: A DDPG algorithms is implemented to solve the environment having continous actions.
 
 ## Getting Started
1. Follow the instructions on the Udacity Repo [Here](https://github.com/udacity/deep-reinforcement-learning/#dependencies)
2. Download the /Unity Reacher environment. Select the environment that matches your operating system:
  - Linux: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
  - Mac OSX: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
  - Windows (32-bit): [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
  - Windows (64-bit): [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
3. Place the downloaded environment `p2_continuous-control/` folder, and unzip (or decompress) the file.
 
## Instructions

 1. To explore the code, open Python Notebook `Continuous_control_Project_SA.ipynb`.
 2. Load the trained weights of Actor and Critic network to see the agent in action.  

