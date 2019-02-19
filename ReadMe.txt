Exercises
1. Modify any one of the programs to produce all possible solutions rather
than just one. How many possible solutions are there for the eight-queens
puzzle? How many of these are rotations of other solutions? How might
you lter out rotations?
92 total, 12 different

2. Can you explain why the sentinel class in the Ob jective-C and Smalltalk versions of the eight-queens puzzle do not need to provide an implementation for the method ndSolution, despite the fact that this message is passed to the neighbor value in the method advance?
Cause the findSolution only returns the canAttack

3. Suppose we generalize the eight-queens problem to the N-queens problem,
where the task is to place N queens on an N by N chessboard. How must
the programs be changed?
It is clear that there are values for N for which no solution exists (consider
N=2 or N=3, for example). What happens when your program is executed
for these values? How might you produce more meaningful output?
you need to change every 8 for a input, there has to be a message for impossible boards.
