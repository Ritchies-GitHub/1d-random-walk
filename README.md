# 1d-random-walk
Simulator of 1-dimensional random walk (unique possible paths)

A person or stock price that starts at position X (integer) and moves up 1 unit or down 1 unit during each minute (integer).  After L minutes, the person or stock ends at position E (integer). Running the code below will ask for start position X, end position E, and amount of time L.  Then it will print the unique paths to go from X to E in L time. 

There are 2 approaches included.  The first approach will randomly iterate through all possible paths until enough unique paths are found.  The second approach will find one possible path and then find the other unique paths via permutations of the first path (more efficient). 

The paths are all printed as numpy arrays grouped in a numpy matrix.  Each row (array) of the matrix is a unique path (a possible path from from X to E in L time). 

Helpful resource: http://mathworld.wolfram.com/RandomWalk1-Dimensional.html

The last cell includes a method to check that the matrices will match from each approach (as long as E, X, L are the same). 
