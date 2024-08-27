# Maze Solver

## Description

This project is a maze solver implemented in Python using Tkinter for graphical visualization. It generates mazes using recursive backtracking and solves them using depth-first search. The project includes components for rendering the maze, managing maze cells, solving the maze, and testing its functionality.

## Project Structure

* `cell.py`: Defines the `Cell` class used to represent individual cells in the maze, including their walls and visited status.
* `graphics.py`: Contains the `Window`, `Point`, and `Line` classes for rendering the maze using Tkinter.
* `maze.py`: Implements the `Maze` class to create and solve the maze using recursive backtracking and depth-first search.
* `test.py`: Includes unit tests for the `Maze` class to ensure its functionality and correctness.
* `main.py`: The main entry point of the application. It initializes the maze, sets up the maze parameters, solves the maze, and displays the result using Tkinter.

## Requirements

* Python 3.x
* Tkinter (usually included with Python installations)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/michaelorina/mazesolver.git
   ```

2. Navigate to the project directory:

   ```bash
   cd mazesolver
   ```

3. Ensure you have Python 3.x installed. Tkinter should be available by default with most Python installations.

## Usage

1. Run the `main.py` script to create and solve a maze:

   ```bash
   python main.py
   ```

   This script will:
   * Initialize a `Window` for maze visualization.
   * Create a `Maze` instance with specified parameters.
   * Solve the maze and print whether it is solvable.
   * Display the maze and solution using Tkinter.

2. To adjust the maze parameters, such as the number of rows, columns, and cell size, modify the `main.py` script.

## Testing

To run the unit tests for the `Maze` class, use the following command:

```bash
python test.py
```

## Acknowledgments

This project was created as part of a guided project at Boot.dev. Special thanks to Boot.dev for the valuable learning resources and guidance provided.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions and improvements are welcome!
