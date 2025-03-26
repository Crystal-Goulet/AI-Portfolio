# Note: This project is based on UC Berkeley's CS188 course materials. The included support files (`mdp.py`, `util.py`, `learningAgents.py`, etc.) are provided solely to demonstrate my original implementations in `valueIterationAgents.py`, `qlearningAgents.py`, and `analysis.py`. This repository is private and intended for job application review only.

# Reinforcement Learning Agents for Gridworld and Pacman

This project implements reinforcement learning agents to solve Markov Decision Processes (MDPs) using value iteration and Q-learning. The agents were applied to environments such as Gridworld, Crawler, and Pacman as part of a class project focused on understanding and applying core reinforcement learning concepts.

# Overview

The goal of this project was to build agents that can learn optimal policies through planning and interaction with an environment. 

The two approaches:

- Value Iteration Agent: An offline agent that solves MDPs by computing value functions through dynamic programming.
- Q-Learning Agent: A model-free agent that learns action values through experience and updates based on the Q-learning update rule.

The project also includes parameter tuning for agent behavior, epsilon-greedy action selection, and optional extensions into approximate Q-learning.


## Files Implemented

The files I used will show "YOUR CODE HERE" above the areas I edited.
The filed I was responsible for were:

- `valueIterationAgents.py`: Value Iteration algorithm and related methods
- `qlearningAgents.py`: Q-learning algorithm, epsilon-greedy action selection, and approximate Q-learning structure
- `analysis.py`: Parameter settings for different policy behaviors

The following support files are included to make the project runnable:

`mdp.py`, `util.py`, `learningAgents.py`, `gridworld.py`, `pacman.py`, `crawler.py`

## How to Run

This project was developed using Python 3.9. Compatibility with Python 3.11+ is not guaranteed due to issues with legacy GUI support.

To run the agents in Gridworld:

bash
python gridworld.py -a value -i 100 -k 10
python gridworld.py -a q -k 100
