# Project-1-
Sudoku solver using backtracking in python

"Welcome to my Sudoku Solver project! This Python-based program is designed to tackle the classic puzzle of Sudoku, using a powerful technique called backtracking. Sudoku is a number puzzle that challenges your logical thinking and problem-solving skills. With this solver, you can input an unsolved Sudoku grid, and the program will intelligently find the solution. It employs a recursive backtracking algorithm that explores possible numbers for each empty cell, undoing and trying a different approach if a conflict is encountered. Whether you're new to Sudoku or a seasoned player, this tool is a handy way to sharpen your skills and enjoy the satisfaction of solving even the most challenging Sudoku puzzles."

This Python project uses backtracking to solve Sudoku puzzles. It includes three key functions:
1. find_next_empty(puzzle): This function locates the next empty cell in the Sudoku puzzle and returns its coordinates or (None, None) if there are no empty cells remaining.

2. is_valid(puzzle, guess, row, col): It verifies if a given guess is a valid choice for a specific cell, ensuring it complies with Sudoku rules, such as not repeating in the same row, column, or 3x3 square.

3. solve_sudoku(puzzle): The main solver function that utilizes recursive backtracking to solve Sudoku. It attempts to fill in empty cells by making valid guesses, updating the puzzle in place. It returns True when a solution is found and False if the puzzle is unsolvable.

An example Sudoku board is provided, and the program attempts to solve it, updating the board in place. This project is a practical tool for Sudoku enthusiasts seeking to solve complex puzzles efficiently.
