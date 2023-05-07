THEORY : 
1. DQN deals with discrete Action Space - as oPposed to DDPG which deals with Continuous Action Space
Features :
(a) Based on Q network ;
(b) Requires a Target network for stability ;
(c) Requires Prioritized Experience Replay for efficient sampling ;
(d) Off-policy method; 
(d) Slow convergence but efficiency is high//
2. Vanilla Policy Gradient :
VPG is an on-policy algorithm
Uses Policy gradients for convergence
VPG can be used for environments with either discrete or continuous action spaces
______________________________________________________________________
PROBLEM STATEMENT : 
Implement theDQNalgorithm to solve the tasks envisioned by the two environments. For the
Pong-v0 environment consider pre-processing of the frames (to arrive at state formulation)
using the following step(s).
• Convert the RGB image into grayscale and downsample the resultant grayscale image.
• Further, one could also perform image subtraction between two successive frames
Any other pre-processing framework could also be used. Although, due to computational
constraints, one may not be able to develop ’best’ pong player, a reasonable pong player
can be developed with a modest laptop (say in 2 to 4 million steps). Include a learning
curve plot showing the performance of your implementation on the game Pong-v0 and
MountainCar-v0. The x-axis should correspond to number of time steps (suitably scaled)
and the y-axis should show the mean n-episode reward (for a suitable choice of n) as well as
the best mean reward. For the pong game, you could implement using normal feed forward
networks or convnets. Accordingly, you may have to do suitable preprocessing. In the case
of MountainCar-v0 environment do plot a graph (one graph) that explains the action choices
of the trained agent for various values of position and velocity
______________________________________________________________________
BACKGROUND OF THE 2 GAMES :
(A) MountainCar-v0 -------------->
A car is on a one-dimensional track, positioned between two "mountains". The goal is to
drive up the mountain on the right; however, the car’s engine is not strong enough to scale
the mountain in a single pass. Therefore, the only way to succeed is to drive back and
forth to build up momentum. Here, the reward is greater if you spend less energy to reach
the goal. //
(B) Pong-v0 ---------------------> 
Pong is a two-dimensional sports game that simulates table tennis. The agent that we
intend to develop usually controls the paddle on the right. It competes with another hardcoded
AI agent who controls the second paddle on the opposite side. Players use the
paddles to hit a ball back and forth. The goal is to develop an agent that can beat the
hard-coded AI player on the other side.
