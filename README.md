# Comparison-of-AI-Search-Algorithms
## Problem Statement:
**The Block Game :** A set of wooden blocks of various shapes and colors are sitting on a table. The goal is to build one or more vertical stacks of blocks. The catch is that only one block may be moved at a time: it may either be placed on the table or placed atop another block. Because of this, any blocks that are, at a given time, under another block cannot be moved.

**Initial state :** Given configuration of blocks and a set of block stacks.

**Actions and transitions :** Move block from the top of one stack onto the table or onto the top of another stack.

**Goal :** A given final configuration of the stacks of blocks.

# Method of Analysis
There are two performance metrics:

1. Number of nodes explored
2. Time taken for execution

Algorithms to compare to find a path :

*   BFS: breadth first search (10 marks)
*   DFS: depth first search  (10 marks)
*   UCS: Uniform-Cost Search  (10 marks)
*   IDS: Iterative Deepning Search (10 marks)
*   A*: A-star seach algorithm [Implement using a different heuristic than the one give in the sample code] (10 marks)
*   IDA\*: Iterative Deepening A\* (10 marks)

We are also using two heuristics for comparison:
1. Heuristic 1 - Count of how many blocks are out of place. 
2. Heuristic 2 - Counts number of moves to be done for every block to reach the desired place.

Tested the performance by varying the number of blocks and using different heuristics. For one comaprison, the initial and final states are same for all algorithms.

## Components
The code can be divided into 5 main components, mainly :
* search.py
* problem.py :
* main.py :
* block_world.py
* random_state_generator.py
## How to Run

## Results

## References
