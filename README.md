# *Reinforcment Learning*

##Understanding the Q Function 

The Q function is central to understanding reinforcement learning.  This README file provides background information to accompany the Jupyter notebook Understanding-Q-Function.ipynb.

A Q function is a function of (action,state) that provides a value for each state and action.  Usually, the state is the robot's position and the action is a directional move (e.g., LEFT).

Each action, state pair has a value.  The robot can chose the optimal value each time (greedy) or with some probability choose a what would appear to be non-optimal value (explore).  Exploration allows the robot to discover new optimal choices that update the Q Function.  

The code is written in Python 3.7 and makes use of the frozen-lake model from the openai gym <https://github.com/openai/gym>.  The final output shows the Q Function after every iteration of training.

Also included in the notebook is a multi-arm bandit example that can be useful for understanding this type of optimization.