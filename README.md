# Sudoko-solver-DSA-Project
# Sudoku Solver in C++

This project implements a **Sudoku Solver** using the **Backtracking Algorithm** in C++. It takes a 9x9 Sudoku board as input with empty cells represented by `0`, and outputs the solved board if a valid solution exists.

 💡 Features
- Solves any valid 9x9 Sudoku puzzle using backtracking
- Checks all Sudoku constraints: row, column, and 3x3 grid
- Simple console input and output

📌 How It Works
The solver uses **recursive backtracking** to fill in numbers from 1 to 9 in each empty cell. It checks for validity using the `isSafe()` function before placing a number. If it leads to a dead end, it backtracks.

 🧮 Input Format
- The user enters 81 integers (space-separated or line-by-line)
- `0` represents an empty cell

📤 Output
- If a solution exists, prints the completed Sudoku grid
- If no solution exists, it notifies the user

🚀 Getting Started

🛠️ Requirements
- A C++ compiler like `g++`

 ⚙️ Compilation
```bash
g++ sudoku_solver.cpp -o sudoku_solver


