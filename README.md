# Navigation-Agent

## 1. Project overview :
A reinforcement learning agent to navigate (and collect bananas!) in a large, square world.

![Banans agent](https://github.com/ZSoumia/Navigation-Agent/blob/master/assets/simulation.gif)

## 2. Task Description : 
**Environment** :

It's similar to Unity Banans collector environment 
![env](https://github.com/ZSoumia/Navigation-Agent/blob/master/assets/env.jpg)

with :
-  37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction
- 4 different actions : 
  * 0 - move forward.
  * 1 - move backward.
  * 2 - turn left.
  * 3 - turn right.
 
**Rewarding strategy** :

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

## 3. Getting started :
If you wish to reproduce this work you need to setup the enviornement by following this section : 

### 3.1- Clone this repository :
`
git clone https://github.com/ZSoumia/Navigation-Agent
`
### 3.2 Set up the environment : 
  Please follow instructions from this [repo](https://github.com/udacity/deep-reinforcement-learning#dependencies)
### 3.2 Download the Unity Environment :
- Select the Unity environement based on your opertaing system : 
  - Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  - Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  - Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  - Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
  
Check out this [link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

==> Place the downloaded file into your cloned project file .

## 4. Project's structure :
- The Agent.py file contains the general structure of the Reinforcement learning agent .
- The Model.py is the used deep learning model to serve as an approximator for our agent.
- Navigation.ipynb is the notebook used to train and evaluate the agent.
