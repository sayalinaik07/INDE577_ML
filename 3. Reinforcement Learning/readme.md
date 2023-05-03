# Reinforcement Learning

![Alt Text](/images/rl.jpg)

Reinforcement learning (RL) is a type of machine learning approach in which an agent learns to behave in an environment by performing certain actions and receiving rewards or penalties based on the outcome of those actions. The goal of RL is to learn a policy that maximizes the total expected reward obtained over a sequence of actions taken by the agent.

In reinforcement learning, the agent interacts with the environment by taking actions, which can lead to changes in the state of the environment and result in receiving feedback in the form of rewards or penalties. The agent uses this feedback to learn which actions are beneficial and which actions should be avoided in order to achieve the desired objective.

Reinforcement learning algorithms typically involve learning an optimal policy, which is a mapping from states to actions that maximizes the expected cumulative reward over time. Some popular RL algorithms include Q-learning, SARSA, and policy gradient methods.

RL is commonly used in various applications, such as robotics, game playing, and autonomous driving, where agents need to learn how to perform tasks by interacting with the environment.

## Maze Challenge

In this game, the player controls a red ball and tries to reach the green square (the finish point) by navigating through the maze. The game has multiple levels with increasing difficulty, and the player needs to avoid obstacles and enemies while reaching the finish point. The obstacles include walls and blue squares that act as traps, while the enemies are the red balls that move randomly in the maze and can kill the player on contact. The game also has a scoring system where the player earns points by reaching the finish point and loses points for hitting obstacles or enemies. The game ends when the player completes all the levels or runs out of points. </br>

![Alt Text](/images/maze1.jpg)

## Reinforcement Learning approach

In Maze Game, the agent is a little blue dot that moves around the maze, and its goal is to reach the red square at the end of the maze. We can use Reinforcement Learning (RL) to solve this game.

We can represent the maze as a grid, where each cell in the grid represents a state, and the possible actions are moving up, down, left or right. At each time step, the agent observes the current state and takes an action, which transitions it to a new state and gives it a reward based on the new state. The goal of the agent is to learn a policy that maximizes its expected cumulative reward over time.


## Output

![Alt Text](/images/maze.gif)

