## Project Overview

This project implements a Q-learning algorithm to train an agent to navigate through a maze and reach a goal. The training process balances exploration and exploitation, using a neural network model and an experience replay system to optimize decision-making over many epochs.

I was provided with starter code and supporting classes (TreasureMaze.py and GameExperience.py) that define the maze environment and the experience replay buffer. My contribution was creating the qtrain() function (shown in this repository), which builds the training loop for the Q-learning process. This function integrates the pseudocode provided in the assignment and expands it into a working implementation that trains the model, evaluates performance, and applies enhancements like epsilon decay for better exploration–exploitation balance.

Connection to Computer Science

This assignment ties into the broader field of computer science in several ways:

## What computer scientists do and why it matters
Computer scientists develop algorithms, systems, and models to solve real-world problems. In this case, reinforcement learning techniques are applied to autonomous decision-making, which has applications in robotics, healthcare, finance, and more. The ability to teach a machine to “learn from experience” demonstrates how computer science helps push boundaries of automation and intelligence.

## Approaching problems as a computer scientist
I approached this project by breaking the problem into smaller, manageable steps first translating pseudocode into a clear structure, then refining action selection, memory storage, and training updates. By iterating and testing, I ensured the program aligned with both the assignment’s requirements and practical Q-learning principles. This problem-solving method analyzing requirements, designing a solution, implementing, and refining is central to computer science.

## Ethical responsibilities
As a computer scientist, I must consider how the tools I create affect both end users and organizations. For AI and machine learning in particular, ethical responsibilities include ensuring models are trained fairly (avoiding biased or harmful data), being transparent about model limitations, and prioritizing safety and trust. In the context of this project, that means designing learning agents responsibly, especially if they were ever applied beyond a classroom setting into real-world systems.

Running the Project

Clone this repository.

Ensure you have Python with the required libraries (NumPy, TensorFlow/Keras).

Run the script to start training the agent in the Treasure Maze environment.

Observe the training progress in the console output, including win rate, loss, and total runtime.
