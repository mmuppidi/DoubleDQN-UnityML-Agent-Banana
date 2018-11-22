# Project 1: Navigation

The goal of this project is train an agent to navigate and collect yellow bananas from Unity ML-Agents toolkit Bananas environment.

### Environment:

The environment is a large square world filled with yellow and blue bananas. The goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas. At every step the agent has access to the state of the environment. The size of the state space is 37. State observed by the agent is ray-based perception of objects around it's forward direction and its velocity.

The actions that agent can take at a point in time are one of move forward, move backward, turn left and turn right; so size of the action space is 4. If the agent collects a yellow banana it receives +1 reward and -1 reward for collecting blue banana. The task is episodic and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the root directory of this repository, and unzip (or decompress) the file. 

### Training the agent

In order to train the agent, open Report.ipynb and run all the cells. 

### Run a trained agent

In order to run a pretrained agent, run all the cells in the Report.ipynb excpet for the training section.

####  For Jupyter notebook newbies

To open the Report.ipynb use the following command from the root of this repository

```
jupyter notebook
```

A webpage will be opened on your browser, click on Report.ipynb, which opens a new page. From here you should be able to run a cell or run everything at once.