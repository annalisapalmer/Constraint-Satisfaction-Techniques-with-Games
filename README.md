# Sudoku Solver with Constraint Satisfaction Techniques

This repository explores solving Sudoku puzzles using techniques from **Constraint Satisfaction Problems (CSPs)**, specifically:
- **AC-3 Inference**
- **Improved Logical Inference**
- **Backtracking Search with Heuristics**

> **Academic Integrity Note**  
> This project reflects my *independent understanding and implementation* of Sudoku-solving algorithms based on general CSP principles.  
> No code directly copied from course materials, solutions, or autograded skeleton files is included here.  
> The structure, logic, and documentation presented here are original and written for learning and demonstration purposes only.

## Project Context

This work builds on well-known AI methods for Sudoku solving:
- Representing the board as a dictionary of cell possibilities
- Enforcing arc consistency using AC-3
- Enhancing inference with unit-based logical checks
- Applying backtracking when constraint propagation is insufficient

While the design and techniques were inspired by concepts taught in an academic setting, this repo is a **personal implementation and extension** of those ideas, consistent with academic policies.

## Techniques Used

- **AC-3 (Arc Consistency Algorithm 3):** Iteratively removes inconsistent values from a cell's domain.
- **Improved Heuristics:** Infers values by examining units (rows, cols, boxes) for unique placements.
- **Backtracking Search:** Applies a recursive search when logic alone cannot solve the puzzle.

## How to Use

The Jupyter notebook guides you through:
1. Board setup
2. Running AC-3
3. Applying improved inference
4. Solving harder puzzles with backtracking

## References

- Russell & Norvig, *Artificial Intelligence: A Modern Approach*
- [AC-3 Algorithm - Wikipedia](https://en.wikipedia.org/wiki/AC-3_algorithm)
- Python Standard Libraries: `collections`, `itertools`, `copy`

---

*This repo is meant to demonstrate my applied understanding of CSPs and Sudoku, and does not include course-specific starter code or evaluation logic.*

