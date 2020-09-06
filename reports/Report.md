## Report
### Hyper Parameters
BUFFER_SIZE = int(1e5)  # replay buffer size
BATCH_SIZE = 64  # minibatch size
GAMMA = 0.99  # discount factor
TAU = 1e-3  # for soft update of target parameters
LR = 5e-4  # learning rate
UPDATE_EVERY = 4  # how often to update the network
Network Architectures = (64, 64) # dense layers

### Result
The agent is trainned by DDQN (Double Deep Q-Learning) for this game. After episode 500, the agent has already got an average score +13 over 100 consecutive episodes.
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
