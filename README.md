# N-Puzzle-Solver-A-Search
An N Puzzle Solver to any Goal State making Use of the Eucledian and Manhattan Heuristcs
This is an N Puzzle Solver Using A Search. It is a generalized version of the implementation by Milan Pecov(See bottom for reference.
It takes in any N puzzle size as a list of lists and returns the steps take to reach the goal. 
The way the heuristics are used within the A* Search is slightly off but you can figure out a way
to make them work for you depending on how you want to evaluate the cost to the goal state as generated. 
You can modify the goal generator to return any goal state you desire. You can implement as many heuristics as
you want on condition that they return an integer.
Add this to the list of functions(heuristics) in the main and make use of it wherever you please.)

The input format  is as follows: For 8 Puzzles : Example [[3,1,5],[,0,2,4],[8,9,7]]. 
It will autogenerate a goal state of the form [[0,1,2],[3,4,5],[6,7,8]] and proceed to solve it and show you the 
steps it took to get there.

It will then print out the frontier size and number of steps take.A lot of the commented code was used to test the correctness and
edge cases like unsolvable instances. An explanation has been included via the geeks for geeks like at the bottom of the IPNYB on
how to evaluate this and an immplementation of the same within the code.
