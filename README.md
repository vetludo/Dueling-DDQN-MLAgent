# Dueling DDQN (Double Deep Q-Learning) mlagent
A example code of Dueling DDQN (Double Deep Q-Learning) for a banana collecting game from Unity ML agent

### Introduction

For this project, I will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent](https://raw.githubusercontent.com/vetludo/ddqn-mlagent/master/assets/banana.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Installation

Install Unity ml-agents.
```
git clone https://github.com/Unity-Technologies/ml-agents.git
git -C ml-agents checkout 0.4.0b
pip install ml-agents/python/
```
Install the project requirements.
```
pip install -r requirements.txt
```


### Report

The agent is trainned by Dueling DDQN (Double Deep Q-Learning) for this game. After episode 500, the agent has already got an average score +13 over 100 consecutive episodes.
After episode 900, the agent gets an average score +16.

Episode 100	Average Score: 0.65\
Episode 200	Average Score: 3.45\
Episode 300	Average Score: 7.80\
Episode 400	Average Score: 9.77\
Episode 500	Average Score: 13.55\
Episode 600	Average Score: 14.91\
Episode 700	Average Score: 15.64\
Episode 800	Average Score: 15.15\
Episode 900	Average Score: 16.27\
Episode 1000	Average Score: 16.07\
Episode 1100	Average Score: 16.22\
Episode 1200	Average Score: 15.91\
Episode 1300	Average Score: 15.26\
Episode 1400	Average Score: 16.32\
Episode 1500	Average Score: 15.46\
Episode 1600	Average Score: 15.96\
Episode 1700	Average Score: 16.71

![report](https://github.com/vetludo/ddqn-mlagent/blob/master/assets/report.png?raw=true)
