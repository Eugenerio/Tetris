# Tetris Game

This is a simple Tetris game implementation using Python and Pygame.

## Features

- Classic Tetris gameplay
- Scoring system
- High score tracking
- Colorful grid and tetrominoes
- Background images

## Requirements

- Python 3.x
- Pygame

## Installation

1. Install Python 3.x from [Python.org](https://www.python.org/downloads/)
2. Install Pygame using pip:
pip install pygame
3. Clone this repository or download as a zip file.

## Usage

1. Navigate to the directory containing the game files.
2. Run the game by executing the following command in your terminal:
python tetris.py


## Controls

- Left arrow: Move tetromino left
- Right arrow: Move tetromino right
- Up arrow: Rotate tetromino
- Down arrow: Soft drop

## Game Scoring

- 1 line cleared: 100 points
- 2 lines cleared: 300 points
- 3 lines cleared: 700 points
- 4 lines cleared (Tetris): 1500 points

The game speeds up as more lines are cleared.

## High Scores

High scores are saved in a file called `record` in the same directory as the game.

## Credits

- Background images: `img/bg.jpg`, `img/bg2.png`
- Font: `fonts/Tetris.ttf`
