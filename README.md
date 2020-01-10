# Project 1: Navigation

### Project Details

For this project, an agent is trained to navigate (and collect bananas!) in a large, square world.  

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Install Python `3.6.8` on your machine (https://www.python.org/downloads/release/python-368/).

2. Install `pip` on your machine by following the instructions in https://pip.pypa.io/en/stable/installing/

3. Install `virtualenv` on your machine by running:

```
$ pip install virtualenv
```

4. Create a virtual environment by running:

```
$ cd this-project-folder/
$ virtualenv venv
```

5. To activate the virtual environment run:

```
$ source venv/bin/activate
```

6. Install the required packages with `pip` by running:

```
$ pip install -r requirements.txt

```

7. Download the Unity environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

8. Place the file in the same folder as the Jupyter Notebook `Navigation.ipynb`, and unzip (or decompress) the file. 

### Instructions

1. To open the notebook in your browser run (make sure your virtual environment is activated):

```
$ jupyter notebook
```

2. Go to `Navigation.ipynb` and open it.

3. Run the first four code blocks to initiate the environment.

4. The 5th code block lets you see how to interact with the environment with random actions.

5. The 6th code block trains the agent until it solves the environment and saves the model weights to `checkpoint.pth` and plots the scores.

6. The 7th code block lets you see how the trained interacts with the environment and prints out the score.