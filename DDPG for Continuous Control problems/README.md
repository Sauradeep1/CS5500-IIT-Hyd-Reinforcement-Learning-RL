The problem involves coding DDPG algorithm and testing in MountainCarContinuous-v0 and
LunarLanderContinuous-v2 environments. Assignment 3 had descriptions of similar environments
where the action space was discrete. On the contrary, the above environments have
continuous action spaces and hence these are continuous control problems. Recall that DDPG
algorithm is mainly used for solving continuous control problems.

(a) Develop a small code snippet to load the corresponding Gym environment(s) and print out
the respective state and action space. Develop a random agent to understand the reward
function of the environment. Record your observations. (3 Points)
(b) Implement the DDPG algorithm to solve the tasks envisioned by the two environments.
Provide corresponding learning graphs in your Jupyter notebooks. (12 Points)
(c) The standard DDPG implementation involves using Ornstein Ulhenbeck (OU) noise for exploration.
For this sub question study the implication of using Gaussian noise for exploration
and report (with reasons) if solving the task takes similar number of episodes.


ALGORITHM :
DDPG is an off-policy algorithm
DDPG can be thought of as being deep Q-learning for continuous action spaces
It uses off-policy data and the Bellman equation to learn the Q-function and uses the Q-function to learn the policy
DDPG can only be used for environments with continuous action spaces
