# Project Description_

The **Deep Q-Learning Maze Solver** project is an implementation of deep reinforcement learning designed to train an agent to navigate and solve mazes. The primary objective of the agent is to find the optimal path to exit the maze, starting from an initial position.

## Key Features

### Customizable Maze
- Users can define custom mazes with different sizes and complexities.
- Mazes are represented by two-dimensional matrices, featuring free cells and obstacles.

### Graphical Representation
- The application provides a visual representation of the maze, with the agent's position highlighted during the training process.
- Users can observe the agent's evolution in the maze.

### Deep Q-Learning
- The agent employs deep Q-learning techniques to learn the state-action mappings that maximize cumulative rewards.
- A deep neural network is utilized as the Q-function approximator.

### Sequential Experience
- The project implements sequential memory to collect the agent's experience during training.
- This experience is leveraged to enhance the model's performance.

### Training Visualization
- The application displays key metrics during training, including the model's loss and success rate in reaching the maze exit.

This project serves as a practical example of implementing deep Q-learning to solve complex problems, such as navigating through dynamic and unknown environments. The agent learns to make intelligent decisions based on received rewards, showcasing its adaptability and continuous learning capabilities.
