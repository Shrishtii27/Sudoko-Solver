# Sudoko-Solver
This project is a C++ implementation of a Sudoku solver. The solver uses backtracking to find a solution for a given 9x9 Sudoku puzzle. It includes features like input validation and clear feedback on whether a solution exists or the puzzle is unsolvable.

Features
Backtracking Algorithm: The solver uses a recursive backtracking approach to fill the Sudoku grid.

Input Validation: The input board is checked to ensure all cells contain valid digits (1-9) or 0 for empty cells.

Safe Placement Check: The solver checks the row, column, and 3x3 grid to ensure that no digit is repeated.

Unsolvable Puzzle Detection: If no solution exists, the program will print an appropriate message.

How It Works
The puzzle is represented as a 9x9 grid, where:
0 indicates an empty cell.
Digits 1-9 represent pre-filled cells.
The solver attempts to fill the grid by placing digits 1-9 in the empty cells, ensuring that no digit is repeated in any row, column, or 3x3 sub-grid.
If a solution exists, it prints the solved Sudoku grid. If not, it prints a message saying the puzzle is unsolvable.
