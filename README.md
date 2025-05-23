# Maze Solver and Recursion Project

This project was developed by Moustafa Neematallah, and implements a set of recursive and iterative algorithms for solving mathematical and maze-related problems in C.

## 🔍 Overview

The project includes:

- Recursive and iterative functions for computing:
  - Minimum value in an array
  - Square root approximation
  - String comparison (case-sensitive and case-insensitive)
- Recursive and iterative solutions for maze traversal
- A randomly generated perfect maze (one unique path between any two cells)

## 📁 Files and Structure

- `main.c`: Contains the `main()` function which tests all implemented functions.
- `Recursion.h` / `project6.cpp`: Implements core logic for min, sqrt, string comparison, and maze solving.
- `MazeParams.h`: Defines maze dimensions and matrix size.
- `recursion.h`: Maze generation, cell marking, and helper logic (e.g., directions, annotations).

## 🧠 Key Features

### ✅ Algorithm Implementations

- `minIt`, `minRec1`, `minRec2`: Iterative and recursive minimum functions
- `sqrtIt`, `sqrtRec`: Square root via binary search
- `strCompare`, `strCompare2`: Lexicographic and case-insensitive string comparisons using recursion

### 🧭 Maze Functionality

- Random maze generation using a DFS-like algorithm
- Recursive maze solver (`solveMazeRec`) with breadcrumb marking
- Iterative maze solver (`solveMazeIt`) using right-hand wall-following algorithm
- Maze visualization using ASCII characters:
  - `#`: Wall
  - ` `: Open space
  - `o`: Breadcrumbs (path taken)

## 🖥️ How to Run

Compile with a C compiler:
```bash
gcc -o maze_solver main.c project6.cpp
./maze_solver
