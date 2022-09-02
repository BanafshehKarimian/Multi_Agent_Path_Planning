# Multi_Agent_Path_Planning
In this project, we implement path planning algorithm for multi-agent system using Reinforcement Learning methods. The action is v*dt, which v is a 2d vector that shows speed of displacement inx and y axis.
The reward function is composed of three terms as follows:
<br />reward = r1 (shortest path goal reward) + r2 (no collision to others) + r3 (no collision to obstacles)
<br />The following algorithms are implemented:
* single agent SARSA, Qlearning, Actor Critic
* multi agent SARSA, MiniMax, Belief Based, Actor Critic
