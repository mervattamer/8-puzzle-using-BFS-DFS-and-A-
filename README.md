# 8-puzzle-using-BFS-DFS-and-A-
This is an AI project that aims to implement 8 - puzzle game using 3 algorithms: Breadth- first search, Depth first search and A* with two heuristics: Manhattan distance and Euclidean distance

This problem appeared as a project in the edX course ColumbiaX: CSMM.101x Artificial Intelligence (AI). In this assignment an agent will be implemented to solve the 8-puzzle game.
An instance of the 8-puzzle game consists of a board holding 8 distinct movable tiles, plus
an empty space. For any such board, the empty space may be legally swapped with any tile
horizontally or vertically adjacent to it. In this assignment, the blank space is going to be
represented with the number 0.
Given an initial state of the board, the search problem is to find a sequence of moves that transitions this state to the goal state; that is, the configuration with all tiles arranged in ascending
order 0,1,2,3,4,5,6,7,8 .
The search space is the set of all possible states reachable from the initial state. The blank
space may be swapped with a component in one of the four directions ’Up’, ’Down’, ’Left’,
’Right’, one move at a time. The cost of moving from one configuration of the board to another
is the same and equal to one. Thus, the total cost of path is equal to the number of moves
made from the initial state to the goal state.

we implemented the 8 puzzle search problem using the three search algorithms:
BFS ,DFS and A*

For the A* (the informed search) we are going to use Manhattan heuristic and Euclidean
heuristic and compare between number of nodes expanded and output paths, and to report
which heuristic is more admissible.
1. Manhattan Distance
It is the sum of absolute values of differences in the goal’s x and y coordinates and
the current cell’s x and y coordinates respectively,
h = abs(current cell:x - goal:x) + abs(current cell:y - goal:y)
2. Euclidean Distance
It is the distance between the current cell and the goal cell using the distance formula
h = sqrt((current cell:x - goal:x)2 + (current cell.y - goal:y)2
)
