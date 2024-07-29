# Sudoku Game

This repository contains a Java-based Sudoku game implemented using Swing. The game features a user-friendly graphical interface where users can solve Sudoku puzzles, generate new puzzles, and view solutions. It includes customizable settings for the difficulty level by allowing users to set the number of empty cells.

## Features

- **Graphical User Interface**: Interactive GUI using Java Swing.
- **Puzzle Generation**: Automatically generates solvable Sudoku puzzles.
- **Difficulty Settings**: Users can change the number of empty cells to adjust the difficulty level.
- **Solution Display**: Option to display the solution of the current puzzle.
- **Input Validation**: Ensures that user inputs follow Sudoku rules.
- **Color-coded Grid**: Visual distinction between different 3x3 sections for better user experience.

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/DonalSaji/Sudoku.git
    cd sudoku-game
    ```

2. **Compile and Run**:
    ```bash
    javac Sudoku.java
    java Sudoku
    ```

## Usage

- **New Game**: Generate a new Sudoku puzzle by selecting "New Game" from the "Game" menu.
- **Show Answer**: Reveal the solution to the current puzzle using the "Show Answer" option in the "Game" menu.
- **Change Number of Empty Cells**: Adjust the difficulty by setting the number of empty cells via the "Change Number of Empty Cells" option in the "Settings" menu.

## Future Improvements

- Implementing multiple difficulty levels beyond just the number of empty cells.
- Adding a timer to track how long it takes to solve the puzzle.
- Providing hints for the next move.
- Adding an option to check for mistakes during the game.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue to discuss potential improvements.
