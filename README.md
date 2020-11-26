# N-Puzzle-solver-with-Search-Algorithms

N-puzzle solver with Search Algorithms including: BFS, DFS (with limited depth), Greedy and A*


There are 2 heuristics for Greedy and A* algorithms. The first one evaluates states with manhattan distance and the second one evaluates states with number of misplaced tiles. 

## Input

The initial state of puzzle would be a list like below:

```
 initial_state = [1, 8, 2, 0, 4, 3, 7, 6, 5]
 ```
 
 ## Output
 
 Output of each search algorithm will be the puzzle solution, number of explored nodes and spent time for search.
 
 ```
BFS Solution is  ['Right', 'Up', 'Right', 'Down', 'Down', 'Left', 'Up', 'Right', 'Down']
Number of explored nodes is  224
BFS Time: 0.005887031555175781
```
