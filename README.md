# Welcome to Atari Games
## task
The Task was to build an AI in Python that "plays" Atari video games using reinforcement learning and the Deep Q-Network models to solve Cart Pole, Space invaders and Pacman games


## Description
 I used the following functions:
1. def__init__(self, state_space, action_space): it initialized the DQN agent, takes inputs and create the neural network
2. def_build_model(self): it constructed the neural network model for the DQN agent using the Keras Sequential API
3. def_remember(self, state, action, reward, next_state, done): it stored experiences in the DQN agent's memory (replay buffer)
4. def_act(self, state): it selected an action in the environment based on an epsilon-greedy policy
5. def_train_env(env, agent, episodes=10, batch_size=32): was a training loop for the DQN agent.
6. warnings for filter warnings 


## Installation
There was no need for any installation as it can be run on local machine using google collab and othe dependencies (stablebaselines3, gymnasium, ...etc) 
which must be installed and imported in the local machines.


## Usage
I run the code on google collab as explained below:
The usage of the code is to train a DQN agent to solve the 'CartPole-v1'/'SpaceInvaders-v4'/'MsPacman-v0' environment. 
By running the train_env() function, the agent will interact with the environment, learn to balance the pole in CartPole, controls the spaceships for accurate shooting in Space invaders, 
and scoring high values in Pacman by eating more.
Also,it should update the neural network weights to approximate the optimal Q-values. 
The agent's performance is expected to improve over the training episodes
env.close(): Closing the environment after training avoid potential memory leaks, and ensure a clean and well-behaved program


### The Core Team
Bukola Veronica Oladele(veronica_b)


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
