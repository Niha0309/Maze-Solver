# Maze-Solver
A simple maze-solving program using Depth-First Search (DFS). The maze is read from a text file, with `A` as the start and `B` as the goal. The goal of this program is to find path from A to B .
## Features
- Load mazes from a text file. walls are any other characters, and spaces are paths. 
- Solve using DFS and Find the solution .
- Save the solution as an image using `Pillow`.
## Usage
Run the program with:
python Maze.py maze.txt ( Example : python Maze.py maze3.txt )
Maze:
Eample : 
██    █
██ ██ █
█B █  █
█ ██ ██
     ██
A██████
Solution:
██****█
██*██*█
█B*█**█
█ ██*██
*****██
A██████
