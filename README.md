OpenAI Gym Solutions
====================

## Requirements

- Python v3.6.5
- anaconda

## How to Run

1. Run `conda create --name a4`
2. Run `source activate a4`
3. Run `conda install --yes --file requirements.txt`
4. Run `pip install gym pyglet`

### Experiments

#### Solving Markov Decision Processes

In this experiment, convergence and performance of value iteration and policy
iteration are compared for 3 different MDPs, including:

1. `FrozenLake-v0`
2. `FrozenLake8x8-v0`
3. `Taxi-v2`

Reproduce the results by running `python analysis/mdp.py`

#### Q-learning Agents

A Q-learner reinforcement learning algorithm was applied to the "Toy Text"
environments. You can reproduce the results by running:

- `python frozen_lake/q_learning.py`
- `python taxi/q_learning.py`
