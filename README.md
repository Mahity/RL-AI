Reinforcement Learning Algorithms - Value Iteration & Q-Learning
This repository contains implementations of two fundamental reinforcement learning algorithms: Value Iteration and Q-Learning, applied to a simple grid world environment.

Problem Description
Grid World Setup:
The environment is a 5x5 grid, where each cell is a state.
The agent can move in four directions: up, down, left, and right.
The agent receives:
A reward of +10 for reaching the goal state.
A reward of -1 for every other step.
Parameters:
Discount factor (gamma): 0.9 (for both algorithms).
Learning rate (alpha): 0.5 (for Q-Learning).
Question 1: Value Iteration Algorithm
Objective:
Implement the Value Iteration algorithm to find the optimal policy for the grid world environment. The goal is to compute the value function for each state and determine the optimal policy after convergence.

Steps:
Initialize the value function for each state.
For each state, update its value by considering all possible actions and the expected reward (based on the Bellman equation).
Repeat the value updates until convergence (when the value function stops changing).
