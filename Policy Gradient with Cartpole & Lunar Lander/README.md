
THE GAMES -------------------------->
Cartpole-v0------------------------>
A pole is attached by an unactuated joint to a cart, which moves along a friction-less track
as shown in Figure 3. The input (or state) to the system consists of cart position, cart
velocity, pole angle and pole velocity at tip. The system is controlled by applying a force
that either pushes the cart to the left or right. The pendulum starts upright, and the goal is
to prevent it from falling over. A reward of +1 is provided for every time-step that the pole
remains upright. The episode ends when the pole is more than 15 degrees from vertical,
or the cart moves more than 2.4 units from the center.

Lunarlander-v2---------------------->
The goal of a Lunar lander, as you can imagine, is to land on the moon. Landing pad is
always at coordinates (0,0). Coordinates are the first two numbers in state vector. Landing
outside landing pad is possible. Fuel is infinite, so an agent can learn to fly and then land
on its first attempt.

There are four discrete actions available: 
1. do nothing, 
2. fire left orientation engine, 
3. fire main engine, 
4. fire right orientation engine. 

The state constitute the coordinates and position of
the lander. This reward function is determined by the Lunar Lander environment. The
reward is mainly a function of how close the lander is to the landing pad and how close
it is to zero speed, basically the closer it is to landing the higher the reward. But there
are other things that affect the reward include firing the main engine deducts points on
every frame, moving away from the landing pad deducts points, crashing deducts points,
etc. The game or episode ends when the lander lands, crashes, or flies off away from the
screen.

