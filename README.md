# TIKTAKTOEGAME
# Tic-Tac-Toe Game in C

The Tic-Tac-Toe Game in C is a classic two-player game where players take turns marking spaces on a 3x3 grid. The objective of the game is to get three of their marks (either "X" or "O") in a horizontal, vertical, or diagonal line. The game ends when a player wins or when all the spaces are filled, resulting in a draw.

The project is implemented using the C programming language and provides a command-line interface for the game interaction. It demonstrates the use of arrays, loops, conditional statements, and user input handling.

## Features

The Tic-Tac-Toe Game project includes the following features:

1. Game Board: The game displays a 3x3 grid representing the Tic-Tac-Toe board. Players mark their moves by choosing the position to place their mark.

2. User Input Handling: The project validates and handles user input to ensure that only valid moves are accepted. It checks for invalid positions, already occupied spaces, and non-numeric characters.

3. Game Logic: The game enforces the rules of Tic-Tac-Toe, such as alternating turns between players, checking for win conditions, and detecting a draw.

4. Win Detection: After each move, the game checks for a winning condition by examining the board state. It determines if a player has achieved three marks in a row (horizontal, vertical, or diagonal).

5. Play Again: After completing a game, the players have the option to play again. If chosen, the game resets the board and starts a new round.

## Project Structure

The project can be organized into the following components:

1. `main.c`: The main file of the project that contains the entry point for the application. It handles the game flow, user input, and interacts with other functions.

2. `board.c` and `board.h`: These files define the functions and structures related to the game board. They handle initializing the board, displaying the current state, updating moves, and checking for win conditions.

3. `player.c` and `player.h`: These files define the functions and structures related to the players. They handle alternating turns, validating moves, and managing player input.

4. `utils.c` and `utils.h`: These files contain utility functions used throughout the project, such as displaying messages, clearing the screen, and handling user input.

## Getting Started

To run the Tic-Tac-Toe Game project, follow these steps:

1. Set up a C development environment on your system, such as Code::Blocks, Dev-C++, or any text editor with a C compiler.

2. Create a new C file and import the project files.

3. Compile and build the project to ensure there are no compilation errors.

4. Run the program to start the game.

## Conclusion

The Tic-Tac-Toe Game project in C provides a simple yet engaging game where players can compete against each other. It demonstrates the use of arrays, loops, conditional statements, and user input handling in C programming. You can further enhance the project by adding features like player names, score tracking, and an AI opponent to make the game more challenging.
