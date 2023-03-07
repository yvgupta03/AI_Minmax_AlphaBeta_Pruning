# AI_Minmax_AlphaBeta_Pruning
AI application of Min-Max algorithm including alpha-beta pruning approach for two agents in cliff-walker scenario

Refer to Project description pdf file for detailed understanding of problem statement. Here I have min-max with and without alpha-beta pruning for cliff-walker grid which is a popular problem when learning Artificial Intelligence. The grid-pattern followed for the problem statement is as shown below:

![image](https://user-images.githubusercontent.com/95063504/223322496-e69bf643-c313-4c49-85be-0481cb1d1bd7.png)

There are different utilities for each cell of the grid based on its color. The cheapest is white, green is expensive and red is basically death zone (or infinite cost). This project aims to study which search technique finds the best path with most reasonable search cost for finite cliff-walker grid, given a start and destination locations. 

Also, there are 2 agents, blue and red. Blue wants to reach the goal location (bottom most right) but Red will try its best to stop this from happening. PART

The results have been visualized at the end of each notebook and Alpha-Beta technique is the best performing heuristic that is reliable enough for such problems.
All 3 parts as per project decription pdf file are implemented in separate python notebooks (folders Part A, Part B, Part C) in python notebooks folder.

There are three parts of this project:
Part A - Minimax search method (without alpha-beta pruning) with the depth limited to two layers (d=2) and print out the returned paths of blue and red agents and the cost of the path for the blue agent.
Part B – Same as Part A but with depth limit to six layers (d=6).
Part C – Same as Part A but with Alpha-Beta Pruning implementation.

### Note :
The code base of each python notebook is flexible enough to accomodate your custom grid size as well as start-end locations and the results are backtracked to show the path according to the search technique applied. 
