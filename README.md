# MazeStudio

MazeStudio is a Python desktop application for creating, editing, solving, and visualizing mazes.

Built with Tkinter, MazeStudio includes tools for maze generation, manual editing, pathfinding algorithms, and animated visual playback.

---

## Features

- Maze Generator
- Maze Editor
- Maze Solver
  - BFS (Breadth-First Search)
  - DFS (Depth-First Search)
  - A* Search
- CSV History Export
- Animated History Viewer
- PNG Maze Export
- Zoom Controls

---

## Screenshots

Coming Soon...

---

## Requirements

- Python 3.10+
- Tkinter
- Pillow

## Installation

```bash
git clone https://github.com/yourusername/MazeStudio.git
cd MazeStudio

pip install pillow

python MazeStudio.py
```

## How to Use

**Generator**
Create random mazes with custom rows, columns, and wall density.

**Editor**
Draw walls, erase cells, place start (A) and end (B) points.

**Solver**
Choose BFS, DFS, or A* to solve the maze.

**History Viewer**
Load exported CSV history files and replay the solving process.
