# Sudoku Solver and Minimum Makespan Problem Solver

This project is a part of my portfolio for Harvard's CS 182: Artificial Intelligence. It contains Python code implementations for solving two distinct types of optimization problems using integer programming and backtracking search techniques: Sudoku puzzles and the minimum makespan problem.

## Sudoku Solver

The Sudoku solver is implemented in two forms:
1. **Backtracking Search Algorithm**: A traditional approach that uses recursive backtracking to explore potential solutions for filling a 9x9 Sudoku grid following standard Sudoku rules.
2. **Integer Programming (IP) Approach**: Utilizes the `cvxpy` optimization package to model and solve Sudoku as an integer programming problem.

### Features

- Solves standard 9x9 Sudoku puzzles.
- Implements forward-checking and the Minimum Remaining Value (MRV) heuristic for efficient backtracking.
- Utilizes integer programming for an alternative solving method via optimization techniques.

### Usage

To solve Sudoku puzzles using these methods, follow the instructions in the Python scripts. You can choose between the backtracking approach and the integer programming approach depending on your preference or the specific requirements of the puzzle you're solving.

## Minimum Makespan Problem Solver

This solver addresses the minimum makespan problem, which involves assigning tasks to a fixed number of machines such that the time to complete all tasks (makespan) is minimized.

### Features

- Takes a list of task times and the number of machines as input.
- Returns the minimum makespan and the assignment of tasks to machines that achieves this makespan.
- Solved using integer programming via the `cvxpy` package.

### Usage

Input your list of task times and the number of machines to the `Min_Makespan_Solver` function. The solver will return the optimal makespan and the task assignments to achieve this optimal solution.
