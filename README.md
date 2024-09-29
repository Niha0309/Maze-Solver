# Maze-Solver
A simple maze-solving program using Depth-First Search (DFS). The maze is read from a text file. The goal of this program is to find path from A to B . Here ,A is the starting point and B is the finishing point . 
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
