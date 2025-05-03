# Robot Coordination Simulation with Obstacles

This project simulates a smart warehouse environment where multiple robots are assigned pickup and delivery tasks while navigating a grid with obstacles. The robots autonomously calculate their paths using Breadth-First Search (BFS) and avoid both static obstacles and each other in real-time.

Features

- Multiple autonomous robots (4 by default)
- Obstacle-aware pathfinding using BFS
- Dynamic task assignment (pickup and delivery points)
- Real-time simulation with Pygame visualization
- Robot-to-robot collision avoidance
- Basic delay-based movement for smoother visuals

Technologies Used

- Python 3
- Pygame (for graphics and simulation)
- Collections (Deque for BFS queue)
- Random (for robot positioning and task generation)

How to Run

1. **Install Dependencies**  
   Make sure you have Python and Pygame installed:
   ```bash
   pip install pygame

Grid Overview
1. Grid Size: 20x20
2. Each cell is navigable unless it's an obstacle.
3. Obstacles are fixed positions that block robot movement.
4. Robots are uniquely colored and labeled with their ID.
