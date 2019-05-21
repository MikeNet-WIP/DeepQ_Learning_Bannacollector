[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

Train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Download the environment
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

2. Place the file in the `p1_navigation/` folder, and unzip (or decompress) the file. 

### Install

1. creat the conda environment 

    `conda create --name enforedlearning python=3.6`
    
    `source activate enforedlearning`
    
    

2. install the latest pytorch with cuda 

    `conda install pytorch-nightly cudatoolkit=10.0 -c pytorch`
    
    
    
3. install pip packages

    `cd enforedlearning/python`
    
    `pip install .`
    
    `cd enforedlearning`
    
    
    
4. get gym for the enviroments

    `git clone https://github.com/openai/gym.git`
    
    `cd gym`
    
    `pip install -e .`
    
    
    
5. (optional) make kernel

    `python -m ipykernel install --user --name drlnd --display-name "drl"`
    


### Instructions

start jupyter notebook `jupyter notebook --allow-root`

Follow the instructions in `Navigation.ipynb` to get started with training your own agent!  

