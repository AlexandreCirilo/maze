# **Random maze generator and solver**

## Introduction

There are many algorithms for randomly generating mazes out there (see [1]). Here, we focus on resorting to the the recursive backtracker as described in [2] for generating the maze. It is one of (if not the) most famous algorithm used for this purpose. It requries memory that is proportional to the size of the maze O(n) (see [5]). We first have to define the number of columns and rows (here, ncols=nrows). The algorithm will do the rest and plot the maze.

## Output
### Maze generation

The maze is randomly generated via the recursive backtracker algorithm.
![alt text](https://github.com/AlexandreCirilo/maze-generator/blob/master/images/maze_1.gif)

### Pathway plotting

In order to use Djikstra;s algorithm to solve the maze, we first need to compute all the possible pathways and represent it into a graph.
![alt text](https://github.com/AlexandreCirilo/maze-generator/blob/master/images/maze_2.png)

### Solver

Solving the randomly generated maze is done via Dijkstra's algorithm, an algorithm for finding the shortest paths between nodes in a graph.
![alt text](https://github.com/AlexandreCirilo/maze-generator/blob/master/images/maze_3.png)

## References

1. [Perfect maze generators](http://people.cs.ksu.edu/~ashley78/wiki.ashleycoleman.me/index.php/Perfect_Maze_Generators.html)
1. [Recursive backtracker](http://people.cs.ksu.edu/~ashley78/wiki.ashleycoleman.me/index.php/Recursive_Backtracker.html)
1. [Breadth-first search](https://courses.cs.washington.edu/courses/cse326/03su/homework/hw3/bfs.html)
1. [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm#Pseudocode)
1. [Big-O notation](http://bigocheatsheet.com/)
