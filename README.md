[//]: # (Image References)

[image1]:https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/img_tennis_play.png "Trained Agent"
## My code from scratch:
`MADDPG`:

[Tennis.ipynb](https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/Tennis.ipynb)

[ddpg_agent.py](https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/ddpg_agent.py)

[model.py](https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/model.py)


![Trained Agent][image1]


# DeepRL-ND-Collaboration-Competition
## [Report](https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/Report.pdf)

### Introduction

For this project, you will work with the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

2. If you haven't setup Unity openAI gym environment, please follow the [instructions in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment.


## Instructions

```bash
$ git clone https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition.git
$ cd DeepRL-ND-Collaboration-Competition
```

Multi-Agent Deep Deterministic Policy Gradient (MADDPG) methods:
* Follow the instructions in [`Tennis.ipynb`](https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/Tennis.ipynb) to train and run the agent!

Use jupyter notebook to open [`Tennis.ipynb`](https://github.com/bmaxdk/DeepRL-ND-Collaboration-Competition/blob/main/Tennis.ipynb)






