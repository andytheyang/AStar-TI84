# AStar-TI84
A* Pathfinding demo for the TI-84 series graphing calculators. Written in the program editor and compiled with Axe Parser (https://www.omnimaga.org/the-axe-parser-project/axe-parser/)

This demo was designed with intent to easily modify the algorithm. By making edits to GetG() and GetH() functions in ASTARLIB.8xp (AStarLibrary.txt), this algorithm can be easily changed to:
1. Greedy DFS (by setting GetG() to 0, eliminating the breadth variable)
2. Dijkstra's (by setting GetH() to 0, eliminating the heuristic variable)

I created this in high school when I first discovered Artificial Intelligence, and created a calculator toy instead of paying attention in class.
