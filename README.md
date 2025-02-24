# Maze Solver Visualization

## Overview
This is a Python-based maze-solving visualization tool built using Pygame. It generates a random solvable maze and allows users to visualize different pathfinding algorithms, including Depth-First Search (DFS), Breadth-First Search (BFS), A* Search, and Dijkstra's Algorithm.

## Features
- **Random Maze Generation:** Generates a new solvable maze on request.
- **Pathfinding Algorithms:** Supports DFS, BFS, A*, and Dijkstra.
- **Visualization:** Displays the search process and final shortest path.
- **User Interaction:** Users can start, reset, and toggle algorithms through buttons.

## Installation
Ensure you have Python installed, then install Pygame:
```sh
pip install pygame
```

## Usage
Run the script:
```sh
python maze_solver.py
```

### Controls
- **Solve Button:** Starts solving the maze with the selected algorithm.
- **Clear Button:** Clears the path visualization.
- **Randomize Button:** Generates a new solvable maze.
- **Algorithm Toggle:** Cycles through available algorithms.

## Algorithms Implemented
- **Depth-First Search (DFS):** Explores paths deeply before backtracking.
- **Breadth-First Search (BFS):** Explores all possible paths layer by layer.
- **A* Search:** Uses heuristics to prioritize efficient paths.
- **Dijkstra’s Algorithm:** Finds the shortest path based on path cost.

## Visualization Colors
- **Black:** Walls
- **White:** Paths
- **Red:** Start Point
- **Green:** End Point
- **Blue:** Visited Nodes
- **Yellow:** Final Shortest Path
- **Algorithm Colors:**
  - DFS: Pink
  - BFS: Purple
  - A*: Dark Blue
  - Dijkstra: Light Blue

## Dependencies
- Python 3
- Pygame
- Heapq (Standard Library)

## License
This project is open-source and free to use.

