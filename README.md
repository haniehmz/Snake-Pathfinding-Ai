# Snake Pathfinding AI

A Snake game project that demonstrates classical Artificial Intelligence search algorithms for pathfinding.

The project visualizes how different search strategies navigate the snake toward the target (fruit) while avoiding obstacles and boundaries.

## Overview

This project focuses on implementing and comparing three fundamental search algorithms:

* Breadth-First Search (BFS)
* Depth-First Search (DFS)
* A* Search (A-Star)

The algorithms automatically determine a path from the snake's current position to the fruit and guide its movement through the game environment.

## Implemented Algorithms

### Breadth-First Search (BFS)

BFS explores nodes level by level and guarantees the shortest path in an unweighted environment.
<p align="center">
  <img width="500" height="520" alt="pic1" src="https://github.com/user-attachments/assets/23e13f87-d877-4364-8cd4-ac6e67793deb" />
</p>
<br>

### Depth-First Search (DFS)

DFS explores paths deeply before backtracking, providing an alternative search strategy with different exploration behavior.
<p align="center">
  <img width="500" height="520" alt="pic2" src="https://github.com/user-attachments/assets/fd704ab6-e8d2-4096-a3d4-52ef7894b9d0" />
</p>
<br>

### A* Search (A-Star)

A* combines path cost and heuristic information to efficiently find optimal paths while reducing unnecessary exploration.
<p align="center">
  <img width="500" height="520" alt="pic3" src="https://github.com/user-attachments/assets/5038f679-0dc9-473f-b45c-78ee3b0001d4" />
</p>
<br>

## Features

* Interactive Snake game environment
* BFS pathfinding implementation
* DFS pathfinding implementation
* A* pathfinding implementation
* Path visualization
* Obstacle avoidance
* Performance comparison of search strategies
* Pygame-based graphical interface

## Technologies Used

* Python
* Pygame

## How to Run

Install dependencies:

```bash
pip install pygame
```

Run the project:

```bash
python Main.py
```

## My Contribution

I implemented the core pathfinding logic for:

* BFS (Breadth-First Search)
* DFS (Depth-First Search)
* A* Search Algorithm

These algorithms are responsible for generating paths from the snake's current position to the target while respecting game constraints.
