# Self-Driving Car Simulation using NEAT and DQN

This project simulates a self-driving car trained using **Reinforcement Learning** techniques. It combines two powerful approaches—**Deep Q-Networks (DQN)** and **NEAT (NeuroEvolution of Augmenting Topologies)**—to adapt a virtual car how to navigate autonomously through an environment.

The simulation is developed in **Python** using **Pygame** for visual feedback and real-time environment interaction.

---

## Project Overview

### 🎯 Objectives

- Build a virtual environment for simulating self-driving behavior.
- Use **Deep Q-Learning** to allow the car to learn by experience and rewards.
- Implement **NEAT** to evolve neural network topologies for better adaptability.
- Visualize training and performance with an interactive simulation window.

---

## How It Works

1. **Deep Q-Network (DQN)**:
   - The agent (car) interacts with the environment and receives rewards based on performance.
   - A deep neural network approximates the Q-value function.
   - Over time, the model learns which actions yield the best long-term rewards (e.g., avoiding collisions, staying on track).

2. **NEAT Algorithm**:
   - Instead of using a fixed architecture, NEAT evolves both the topology and weights of the neural network.
   - The population of agents is evaluated each generation, and successful architectures are selected, mutated, or recombined.
   - This enables adaptive learning in highly dynamic and non-linear environments.

3. **Simulation with Pygame**:
   - The environment is visualized using Pygame.
   - The car moves in a 2D space with walls, turns, and obstacles.
   - Users can observe training progress, car decisions, and environment interactions in real time.

---

## Key Highlights

- Combines **model-free learning** (DQN) with **evolutionary strategies** (NEAT).
- Real-time simulation to test and debug agent behaviors visually.
- Performance improves with training as the car learns to navigate longer without collisions.
- Modular code structure to easily switch between DQN and NEAT training modes.
- Great educational project to understand RL, neuroevolution, and simulation environments.

---

## Skills Demonstrated

- Reinforcement Learning (DQN, Epsilon-Greedy Strategy)
- Evolutionary Algorithms (NEAT)
- Neural Network Optimization
- Simulation Development with Pygame
- Autonomous agent training and evaluation