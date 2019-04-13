# About this project

This repository contains the solution to the Banana Unity Environment ([github repository](https://github.com/Unity-Technologies/ml-agents)). This project is part of Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program. The goal is to implement an agent walking thorugh a space where there are yellow ones and blue bananas. The agent gets a reward of +1 if it catches a yellow banana and -1 if it catches a blue one. 

There are foUr available actions:

- `0` - walk forward
- `1` - walk backward
- `2` - turn left
- `3` - turn right

The state space dimension is 37.  This an episodic task. The environment is considered solve if the average score over 100 consecutive episode surpasses +13. 



# Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Place the file in `bin/` directory, and unzip (or decompress) the file.

3. Install all the dependencies from `navigation.txt`.

# Instructions
The file `dqn_agent.py` corresponds to the agent class and includes the methods for interacting with the environment and training the agent. `model.py` contains the neural network architecture.   `Navigation.ipynb`displays the solution. 
