<h1 align="center">2048 Game</h1>
2048 is a popular single-player sliding tile puzzle game originally created by Gabriele Cirulli in 2014. The objective of the game is to slide numbered tiles on a 4x4 grid to combine them and create a tile with the number 2048. This implementation of 2048 is developed in JavaScript and is designed to run in modern web browsers.

## Features
Simple and intuitive user interface
Smooth animations for tile movements
Responsive design for desktop and mobile browsers
Score tracking and display

## Game Rules
* Grid: The game is played on a 4x4 grid.

* Tiles: Each tile contains a number, starting from 2. New tiles appear randomly in an empty spot on the board with a value of either 2 or 4.
* Moves: Players can move the tiles up, down, left, or right using the arrow keys. All tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid.
* Merging Tiles: When two tiles with the same number collide while moving, they merge into one tile with the combined value of the two original tiles (e.g., 2 + 2 = 4).
* Objective: The goal is to create a tile with the number 2048. Players can continue playing to achieve higher scores by creating larger numbered tiles.
* Game Over: The game ends when the grid is full and no more moves are possible.

## How to Play
1. Start the Game: Open the index.html file in your web browser.

2. Controls:
   * Arrow Keys: Use the arrow keys to move the tiles.
   * Up Arrow: Move tiles up.
   * Down Arrow: Move tiles down.
   * Left Arrow: Move tiles left.
   * Right Arrow: Move tiles right.

3. Gameplay Strategy:
   * Plan Ahead: Consider future moves to avoid getting stuck.
   * Keep High Tiles Together: Try to keep your highest number tiles in one corner for better control.
   * Avoid Random Moves: Make strategic moves to ensure you have room to maneuver tiles.

## License
This project is licensed under the [MIT License](./LICENSE).

## Acknowledgements
Gabriele Cirulli for the original 2048 game concept.