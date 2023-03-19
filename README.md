# Efficient-Sudoku-MRV-Backtracking

Efficient-Sudoku-MRV-Backtracking is a fast Sudoku solver that uses the Minimum Remaining Values (MRV) heuristic and backtracking algorithm for an optimized solution approach.

## Features

- Solves Sudoku puzzles quickly using MRV heuristic and backtracking
- Uses constraint satisfaction techniques for optimization

## Installation

Simply clone the repository to your local machine:

```bash
git clone https://github.com/Mohamad-Jaallouk/Efficient-Sudoku-MRV-Backtracking.git
```

## Usage

1. Provide a Sudoku puzzle as a 9x9 list of lists, with empty cells represented by 0:

```python
puzzle = [
    [4, 0, 0, 0, 0, 0, 8, 0, 5],
    [0, 3, 0, 0, 0, 0, 0, 0, 0],
    ...
]
```

2. Call the `backtrack` function with the puzzle as an argument:

```python
solution = backtrack(puzzle)
```

3. The solved Sudoku puzzle is returned as a 9x9 list of lists.
