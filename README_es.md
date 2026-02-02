# Portafolio de Proyectos Personales

> *Lee esto en [Inglés](README.md)*

Este repositorio es una colección de proyectos que he programado durante mis estudios de **Ingeniería Informática**. Mi objetivo es aplicar mis conocimientos para construir diversas aplicaciones.

## Proyectos Realizados

### [Neural Othello](https://github.com/edu-gutierrez/neural-othello)

Agente de deep Reinforcement Learning autónomo basado en AlphaZero de DeepMind(Google) que aprende para jugar al Othello(Reversi) mediante auto-juego.

* **Tech Stack:** Python, PyTorch, Pickle, NumPy, Pygame.
* **Detalles:**
  * Implementación de **Bloques Residuales** para procesar el tablero como una imagen.
  * Implementación de **MCTS** para encontrar las mejores jugadas.
  * Bucle de entrenamiento completo con data augmentation para multiplicar los datos de entrenamiento.

### [Blackjack Q-Learning](https://github.com/edu-gutierrez/blackjack-rl)

Agente de Reinforcement Learning autónomo que aprende la estrategia óptima de Blackjack mediante auto-juego.

* **Tech Stack:** Python, Pickle.
* **Detalles:**
  * Implementación desde cero de **Q-Learning** y la **Ecuación de Bellman**.
  * La IA aprendió la estrategia por si sola (cuando doblar/plantarse/pedir).
  * Incluye modo de juego en terminal donde la AI te hace de "asesor" diciendote la mejor jugada.

### [Algorithm Visualizer](https://github.com/edu-gutierrez/algorithm-visualizer)

Herramienta de escritorio para visualizar el comportamiento de algoritmos en tiempo real.

* **Tech Stack:** Python, PyQt, NumPy, PyQtGraph.
* **Detalles:**
  * Implementación de +20 algoritmos de ordenamiento, 5 de pathfinding y 4 de clustering.

### [GL-Scrapbook (Motor Gráfico Experimental)](https://github.com/edu-gutierrez/gl-scrapbook)

Entorno de pruebas gráficas desde cero para entender el funcionamiento de un motor gráfico y la pipeline de renderizado.

* **Tech Stack:** C++, OpenGL, GLSL, GLM.
* **Detalles:**
  * Renderizado sin motores (no Unity/Unreal).
  * Implementación manual de shaders de iluminación (Phong) y mapeado de texturas.
  * Sistema de cámara y gestión de transformaciones en 3D.

### [TicTacToe (Minimax AI)](https://github.com/edu-gutierrez/tictactoe-sfml)

Implementación dual (CLI y GUI) enfocada en la teoría de juegos.

* **Tech Stack:** C++, SFML.
* **Detalles:**
  * **Core:** Algoritmo Minimax recursivo (IA imposible de ganar).
  * **Arquitectura:** Desacoplamiento entre la lógica del juego y la interfaz, permitiendo pasar de Terminal a SFML reutilizando el backend.

### [Hell Masquerade (Global Game Jam 2026)](https://github.com/edu-gutierrez/hell-masquerade)

Juego completo desarrollado solo en 48h.

* **Tech Stack:** C#, Unity.
* **Estado:** Completo y jugable.
* **Focus:** Prototipado rapido y jugabilidad.
