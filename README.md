# Udacity project navigation

![sample](./images/banana-collector.gif)

## Udacity project for garbage collector using Unity ML agents

### Project description
training an agent using Deep Q networks to navigate (and collect bananas!) in a large, square world. 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.


### Solution

This project has been solved on a Jupyter notebook 

Follow the instructions in `Navigation.ipynb` to get started with training your own agent!  

#### Results:
![results](./images/Results.png)


### Requirements
Libraries:
pip install unityagents
pip install numpy
pip install matplotlib
install pytorch folliwng the instructions on the pytorch website: https://pytorch.org/get-started/locally/

You will need the folder named: Banana_Windows_x86_64 and the jupyter notebook named Navigation.ipynb

For this case you might not need to install Unity3D. This is because the files for the environment were provided by the Udacity Nano degree in Deep reinforcement learning.


