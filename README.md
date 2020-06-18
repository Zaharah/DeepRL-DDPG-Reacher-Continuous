# Continuous Control with DDPG
---
## Introduction
Implementation of DDPG algorithms to solve the contiunous action space of Unity Reacher Environment :rocket:.


 - *Agent*: A double-jointed arm that can move to targer location. 
 - *Environment*: In the Reacher environment, the target location is a moving ball rotating around the agent. 
 - *Action size*: The action size is four with continuous nature, where a single action can take any value between -1 to 1. 
 - *Observation space*: The state space consists of 33 variables corresponding to position, rotation, and angular velocities of the arm. 
 - *Rewards*: There is +1 reward of each step the agent’s hand is at target location. 
 - *Goal*: The environment is considered solved when an agent accumulates an average reward of +30 for 100 consecutive episodes. 
 - *Apporach*: A DDPG algorithms is implemented to solve the environment having continous actions.
 
 ## Getting Started
 

