# Conways Game of Life

Given a 2D array and a number of generations, compute n timesteps of Conway's Game of Life.

The rules of the game are:

1. Any live cell with fewer than two live neighbours dies, as if caused by underpopulation.
1. Any live cell with more than three live neighbours dies, as if by overcrowding.
1. Any live cell with two or three live neighbours lives on to the next generation.
1. Any dead cell with exactly three live neighbours becomes a live cell.

Each cell's neighborhood is the 8 cells immediately around it (i.e. Moore Neighborhood). The universe is infinite in both the x and y dimensions and all cells are initially dead - except for those specified in the arguments. The return value should be a 2d array cropped around all of the living cells. (If there are no living cells, then return [[]].)
