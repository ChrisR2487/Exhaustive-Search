# Exhaustive-Search

In the game of magic grids, the game designer selects n * m cards with integers on them, and secretly arranges them in a grid with n rows and m columns. They then tell the player 
a number of facts about the sums of a row or a column, for example, "the sum of column 1 is 20." Note that they can lie; however, the must tell the player how many of the facts 
that were stated were lies.  The goal of the player is to determine bounds on the size of the cards at each position.

My algorithm updates the lower and upper bounds when considering a consistent permutation, and since I consider all possible permutations, these bounds must be correct.
It runs in OMEAGA(n*m)!) 
