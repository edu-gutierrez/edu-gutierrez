# Portfolio of personal projects

> *Read this in [Spanish](README_es.md)*

This repo is a collection of projects I programmed during my studies of **Computer Science**. My objectives are to apply the knowledge earned to build different applications.

## Projects Done

### [Neural Othello](https://github.com/edu-gutierrez/neural-othello)

Deep Reinforcement Learning agent based on Google DeepMind's AlphaZero, that learns to play Othello by self play.

* **Tech Stack:** Python, PyTorch, Pickle, NumPy, Pygame.
* **Details:**
  * Implementation of **Residual Blocks** to process the board as an image.
  * Implementation of **MCTS** to find the best moves.
  * Automated training loop with data augmentation to enhance the dataset.

### [Blackjack Q-Learning](https://github.com/edu-gutierrez/blackjack-rl)

Reinforcement Learning agent that learns the optimal way to play Blackjack by self play.

* **Tech Stack:** Python, Pickle.
* **Details:**
  * Implementation from scratch of **Q-Learning** and **Bellman Equation**.
  * The AI learnt the strategy by itself (when to double/strand/hit).
  * includes a terminal game mode where the AI is your "advisor" and tells you the best play each turn.

### [Algorithm Visualizer](https://github.com/edu-gutierrez/algorithm-visualizer)

Desktop tool to visualize how algorithms work in real time.

* **Tech Stack:** Python, PyQt, NumPy, PyQtGraph.
* **Details:**
  * Implementation of +20 algorithms of sorting, 5 of pathfinding and 4 of clustering.

### [GL-Scrapbook (Experimental Graphics Engine)](https://github.com/edu-gutierrez/gl-scrapbook)

Experimental graphics engine from scratch to learn how a graphics engine works and the render pipeline.

* **Tech Stack:** C++, OpenGL, GLSL, GLM.
* **Details:**
  * Engine-free rendering (no Unity/Unreal).
  * Manual implementation of lighting shaders (Phong) and texture mapping.
  * Camera system and 3D transformations management.

### [TicTacToe (Minimax AI)](https://github.com/edu-gutierrez/tictactoe-sfml)

Dual implementation (CLI and GUI) focused on game theory.

* **Tech Stack:** C++, SFML.
* **Details:**
  * **Core:** Minimax recursive algorithm (AI impossible to win).
  * **Architecture:** Decoupling of game logic and interface, enabling the transition from Terminal to SFML by reusing the backend.

### [Hell Masquerade (Global Game Jam 2026)](https://github.com/edu-gutierrez/hell-masquerade)

A complete game developed in just 48 hours.

* **Tech Stack:** C#, Unity.
* **Status:** Completed & Playable.
* **Focus:** Rapid prototyping and game feel.
