# Sudoku Solver

Solving Sudoku with Backtracking Algorithm

- Purpose: 
  - The code aims to solve Sudoku puzzles using a backtracking algorithm, ensuring that Sudoku rules are followed.

- Key Components:
  - Board Representation:
    - The Sudoku board is a 9x9 grid represented by a 2D list, with 0s indicating empty cells.
  - Printing the Board:
    - The print_board function displays the Sudoku board in 3x3 sub-grids, resembling the traditional layout.
  - Finding Empty Cells:
    - The find_empty function locates the position of the first empty cell on the board.
  - Checking Validity:
    - The is_valid function verifies if a number can be placed in a cell without violating Sudoku rules.
  - Solving the Puzzle:
    - The solve function employs a recursive backtracking algorithm to fill empty cells with valid numbers, iterating until the puzzle is solved.
  - Main Execution:
    - The initial and solved boards are printed using the solver function.

- How It Works:
  - The backtracking algorithm fills empty cells with potential numbers, checking for validity and backtracking when reaching a dead-end. This process continues until a valid solution is found or the puzzle is determined unsolvable.
