DQN deals with discrete Action Space - as ooposed to DDPG
Features :
Based on Q network
Requires a Target network for stability
Requires Prioritized Experience Replay for efficient sampling
Off-policy method
Slow convergence but efficiency is high
______________________________________________________________________
MountainCar-v0
A car is on a one-dimensional track, positioned between two "mountains". The goal is to
drive up the mountain on the right; however, the car’s engine is not strong enough to scale
the mountain in a single pass. Therefore, the only way to succeed is to drive back and
forth to build up momentum. Here, the reward is greater if you spend less energy to reach
the goal. 
Pong-v0
Pong is a two-dimensional sports game that simulates table tennis. The agent that we
intend to develop usually controls the paddle on the right. It competes with another hardcoded
AI agent who controls the second paddle on the opposite side. Players use the
paddles to hit a ball back and forth. The goal is to develop an agent that can beat the
hard-coded AI player on the other side.
