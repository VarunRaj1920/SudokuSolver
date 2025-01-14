# SudokuSolver
Welcome to the **Sudoku Solver** project! 🎉 This project features a powerful Sudoku solver implemented in Python, complete with a graphical user interface (GUI) using Pygame. Whether you're a Sudoku enthusiast looking to solve puzzles or a developer interested in algorithmic problem-solving, this project has something for you!

## 📦 Project Structure

- **assets/**: Contains images and GIFs for the project.
- **requirements.txt**: Lists the dependencies required to run the project.
- **SudokuSolver.py**: Contains the core logic for solving Sudoku puzzles.
- **SudokuGUI.py**: Implements the graphical user interface for the Sudoku solver.

## 🧩 How It Works

The Sudoku Solver uses a backtracking algorithm to solve Sudoku puzzles. Here's a brief overview of the key components:

- **SudokuSolver Class**: This class contains methods for solving Sudoku puzzles, checking if a number can be placed in a cell, generating a new Sudoku board, and removing numbers to create a playable puzzle.
- **Dynamic Backtracking**: The solver employs dynamic backtracking techniques, including constraint propagation and heuristic selection, to efficiently navigate the search space and find solutions.

### Key Features

- **Random Board Generation**: The solver can generate a new Sudoku board with a specified number of cells removed.
- **Graphical User Interface**: The GUI allows users to visualize the Sudoku board and interact with the solver.
- **Hints**: Users can request hints while solving the puzzle.

## 🚀 Getting Started

Follow these steps to get the Sudoku Solver up and running on your local machine:

### Prerequisites

Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/VarunRaj1920/SudokuSolver.git
   cd SudokuSolver

2. **Install the Dependencies**: Once the virtual environment is activated, install the required packages by running:
   ```bash
   pip install -r requirements.txt

3. **Running the Application**: Start the GUI. To launch the Sudoku GUI, run the following command:
   ```bash
   python SudokuGUI.py

Interact with the Solver
Use the SPACE key to solve the puzzle.
Press H to get a hint for the next move.
