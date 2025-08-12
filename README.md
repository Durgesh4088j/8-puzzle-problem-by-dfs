# 8-puzzle-problem-by-dfs
📌 Aim 

The aim of this project is to implement a Depth-First Search (DFS) algorithm to solve the 8-puzzle problem. The program finds a path from a given start state to the goal state by exploring all possible moves systematically. 

 

Shape 

📌 Problem Statement 

The 8-puzzle problem consists of a 3x3 grid with tiles numbered 1–8 and one empty space (denoted by 0). 
The objective is to move the tiles by sliding them into the empty space until the puzzle matches the goal configuration: 

Given an initial state from the user, the program must: 

Traverse the puzzle states using DFS. 

Record all visited states. 

Print the traversal order. 

Reconstruct and display the final path from start to goal. 
 

Shape 

📌 Algorithm Used: Depth-First Search (DFS) 

Start with the initial state and push it onto a stack. 

While the stack is not empty: 

Pop the top state. 

If the state has already been visited, skip it. 

Mark the state as visited. 

If it matches the goal state, terminate and reconstruct the path. 

Otherwise, generate all possible child states (by sliding the blank tile). 

Push unvisited child states onto the stack. 

If the stack becomes empty without reaching the goal, return no solution. 
