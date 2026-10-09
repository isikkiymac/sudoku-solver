# Sudoku Solver with Backtracking

A Sudoku solver using backtracking search with the Minimum Remaining Value (MRV) heuristic and forward checking.

## Overview
Built as part of Columbia University's Artificial Intelligence course (COMS 4701). Solves 9x9 Sudoku puzzles by framing the problem in terms of variables (81 cells), domains (1-9), and constraints (row/column/box uniqueness).

## Tech Stack
- **Language:** Python 3
- **Algorithm:** Backtracking search with MRV + forward checking

## Key Features
- **Constraint satisfaction formulation:**
  - 81 variables (one per cell)
  - Domain {1-9} for each
  - Row, column, and 3x3 box constraints
- **Minimum Remaining Value (MRV) heuristic** — picks most constrained variable first
- **Forward checking** — prunes domains as assignments are made
- **Efficient solving** — well under 1 minute per board
- **Batch testing** — processes hundreds of puzzles and reports statistics

## Results
- Solves all provided sample puzzles
- Runtime statistics: min, max, mean, standard deviation
- Handles "world's hardest Sudoku" puzzles

## What I Learned
- Constraint satisfaction problems (CSPs)
- Backtracking search optimization
- Heuristic design for variable/value ordering
- Forward checking for domain reduction

## Note
This project was completed for a course. Source code is available upon request due to course policy restrictions. I'm happy to discuss the CSP formulation and heuristic design in an interview.
