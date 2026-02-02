# SELF-SNAKE-AGENT-GAME 

'''Introduction
This is a Pytorch implementation of DQN Agent

In this project, I represent a simple selF-snake playing agnet using the DQN algorithm

Deep Q-Network (DQN) : 
DQN is a type of reinforcement learning algorithm that utilizes deep neural networks to help an agent learn the best course of action within an environment.

Here's the gist:

The agent interacts with the environment (think video game) and gathers experiences. These experiences include the state it was in, the action it took, the reward it received, and the new state it transitioned to.
DQN utilizes a technique called experience replay. It stores these experiences in a memory buffer, allowing the agent to learn from them even after they occur.
A deep neural network, called the Q-network, estimates the Q-value for each state-action pair. The Q-value signifies the expected future reward the agent can obtain by taking a specific action in a particular state.
The DQN trains by updating the Q-network's estimates using experiences from the replay memory. It adjusts the network to make its Q-value predictions more accurate over time.
Once trained, the agent leverages the Q-network to make decisions. It selects the action with the highest Q-value in a given state, aiming to maximize future rewards.
In essence, DQN learns from experience, predicts future rewards, and makes decisions to optimize them.

Usage: 
Clone the repo : https://github.com/ashish230231/SELF-SNAKE-AGENT-GAME-.git
Install the requirements
Run the model : 
python agent.py
