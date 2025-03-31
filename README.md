# Tic-Tac-Toe Game

## Overview
This project implements a simple **Tic-Tac-Toe** game using HTML, CSS, and JavaScript. The game allows two players to take turns playing on a 3x3 grid until one player wins by forming a row, column, or diagonal of matching symbols, or until the game ends in a draw.
## 🚀 Live Demo
[Click here to play Tic-Tac-Toe!](https://joshb-hub.github.io/Tic-Tac-Toe/)

## Screenshots
![TicTacToe Screenshot](Screenshot%202025-04-01%20014228.png)
![TicTacToe Screenshot](Screenshot%202025-04-01%20014359.png)
![TicTacToe Screenshot](Screenshot%202025-04-01%20014349.png)
![TicTacToe Screenshot](Screenshot%202025-04-01%20014244.png)


## Reference
Refered from Apna College https://github.com/shradha-khapra/JavaScriptSeries/tree/main/TicTacToe

## Features
- Two-player mode (Player X and Player O).
- Winner detection for all possible win patterns (rows, columns, diagonals).
- Draw detection when all cells are filled with no winner.
- Easy-to-use reset button to start a new game.
- Can start a new game after result declaration.
- Simple and clean user interface.

## How to Play
1. **Player X** goes first. Click on an empty square to mark it with an "X".
2. **Player O** goes next. Click on an empty square to mark it with an "O".
3. Players take turns until one wins by forming a row, column, or diagonal of matching symbols.
4. If all squares are filled and no one has won, the game ends in a draw.
5. To play again, click the "Restart" button to reset the board.

## Game Mechanics
- The game board consists of 9 cells arranged in a 3x3 grid.
- Players alternate turns by clicking on empty cells.
- The game checks after each move for any winning pattern.
- If a player forms a winning pattern (3 marks in a row, column, or diagonal), they are declared the winner.
- If no more moves are possible and there is no winner, the game is declared a draw.

## Installation
You can run this game locally by simply opening the HTML file in your browser. No additional installations are required.

### Steps:
1. Clone or download this repository.
2. Navigate to the project folder.
3. Open the `index.html` file in any modern browser to start playing.

## Files

- **index.html**: Contains the structure of the Tic-Tac-Toe game board and UI elements.
- **style.css**: Styles the game board and controls the layout and appearance.
- **script.js**: Contains the game logic for player turns, win conditions, and reset functionality.

## Technologies Used

- **HTML**: For structuring the game board and UI.
- **CSS**: For styling the layout and design.
- **JavaScript**: For handling game logic, player interactions, and dynamic updates.


## Cloning the repository
```bash
git clone https://github.com/Joshb-hub/Tic-Tac-Toe.git
cd Tic-Tac-Toe
open index.html

