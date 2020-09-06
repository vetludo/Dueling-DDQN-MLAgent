# ddqn-mlagent
A example code of ddqn (double deep Q-learning) for a banana collecting game from Unity ML agent

### Introduction

For this project, I will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent](https://raw.githubusercontent.com/vetludo/ddqn-mlagent/master/banana.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Report

The agent is trainned by DDQN (Double Deep Q-Learning) for this game. After episode 600, the agent has already got an average score +13 over 100 consecutive episodes.
After episode 1600, the agent gets an average score +16.
