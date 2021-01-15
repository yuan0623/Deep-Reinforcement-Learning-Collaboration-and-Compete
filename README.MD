[//]: # (Image References)

[image1]: https://video.udacity-data.com/topher/2018/May/5af7955a_tennis/tennis.png "Tennis"
# Deep Reinforcement Learning Nanodegree Project 3 Collaboration and Competition
This repository contains submission of the project 3 of Udacity's [Deep Reinforcement learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program.
![Tennis][image1]
### Problem description
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.
#### states
The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket.
#### actions
Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

#### goal
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

### Getting Started
#### local environment set up
1. Create and activate a new environment with Python 3.6 using  [Anaconda](https://www.anaconda.com/).
  - **Linux** or **Mac**
  ```bash
  conda create --name drlnd python=3.6
  source activate drlnd
  ```
  - **Windows**
  ```bash
  conda create --name drlnd python=3.6
  activate drlnd
  ```
2. Install OpenAI gym, the instruction can be find [here](https://github.com/openai/gym)
3. Install **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control)
4. Install the **box2d** environment by following the instructions [here](https://github.com/openai/gym#box2d).
5. Install the **pytorch** package by following the instruction [here](https://pytorch.org/get-started/locally/) .

As this submission is done using the workspace provided by the Udacity, the Unity environment is not included. If you wish to interact with the Unity environment, feel free to download the compiled Unity environment here.
- Linux: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- Mac OSX: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
- Windows (64 bit): [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)   

After you have downloaded these compiled Unity environment, you need to specify the file path in the line of `Tennis.ipynb`
### Instructions
follow the instruction of `Tennis.ipynb`, simply run the code cell with sequential manner.
**Note**: please run the Jupyter notebook under drlnd environment.


### Results
In the end, the agent solve this environment in 787 episodes with an average score equals to 0.5.
