# Connect Four Terminal Game

Connect Four Terminal is a classic two-player connection game where players take turns dropping colored discs into a seven-column, six-row vertically suspended grid. The goal is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs. This version of the game is implemented in C++ and runs in the terminal.

## Features

- **Simple Gameplay**: Easy to understand rules and gameplay.
- **Terminal Interface**: Play directly in your terminal.
- **Two-Player Mode**: Enjoy playing with a friend.
- **Win Detection**: Automatically detects and announces the winner.
- **Tie Condition**: Handles and announces a tie if the board is full without a winner.

## How to Play

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/connect-four-terminal.git
    ```
2. Navigate to the project directory:
    ```bash
    cd connect-four-terminal
    ```
3. Compile the game using a C++ compiler, e.g., g++:
    ```bash
    g++ -o connect_four connect_four.cpp
    ```
4. Run the game:
    ```bash
    ./connect_four
    ```
5. Follow the on-screen instructions to play. Players take turns entering a column number (1-7) to drop their discs.

## Game Rules

- Players take turns dropping one disc at a time into any of the non-full columns.
- The first player to form a line of four discs horizontally, vertically, or diagonally wins the game.
- If the board fills up before any player forms a line of four, the game is declared a tie.

## Contribution

Contributions are welcome! If you find a bug or have a feature request, please open an issue. Feel free to fork the repository and submit a pull request with your enhancements.

## Acknowledgments

- This game is inspired by the classic Connect Four game by Milton Bradley (now Hasbro).


