# Tic-Tac-Toe-Game
Interactive 2-player Python Tic Tac Toe game featuring custom board rendering, turn validation, win/tie detection, and game replays

# Python Tic Tac Toe Game

An interactive, two-player terminal-based Tic Tac Toe game written in Python and optimized for Jupyter Notebooks.

## Features

- **Interactive 2-Player Gameplay:** Takes input from Player 1 and Player 2 sequentially.
- **Dynamic Board Updates:** Uses `from IPython.display import clear_output` to clear and refresh the display after every move.
- **Numpad Mapping:** Players select positions using digits `1-9`, directly corresponding to a standard keyboard numpad layout.
- **Input & Move Validation:** Prevents players from picking invalid numbers or overwriting already occupied spaces.
- **Win & Tie Detection:** Automatically evaluates horizontal, vertical, and diagonal win conditions or ties.
- **Replay Option:** Prompts players to restart a new game when a round ends.

## How to Play

### Board Layout
The board grid maps directly to your keyboard's numpad:

7 | 8 | 9

4 | 5 | 6

1 | 2 | 3

### Game Setup & Rules
1. Run all cells in the Jupyter Notebook (`.ipynb`).
2. Player 1 chooses their marker (`X` or `O`). Player 2 is automatically assigned the remaining marker.
3. Players take turns entering a position number (`1-9`) to place their marker.
4. The first player to align three markers horizontally, vertically, or diagonally wins!
5. If all 9 spots are filled without a winner, the game results in a tie.

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab (`IPython` library included by default)
