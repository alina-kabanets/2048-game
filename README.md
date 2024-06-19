# 2048 Game
2048 is a single-player sliding tile puzzle game, written by Italian web developer Gabriele Cirulli. The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

# Rules of 2048:
2048 is played on a 4×4 grid, with numbered tiles that slide smoothly when a player moves them using the four arrow keys. Each time you slide, a new tile will randomly appear in an empty spot on the board. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move.

You can check the DEMO here: https://alina-kabanets.github.io/2048-game/
Don't play for too long!)

# I had the following requirements:
1. The game field is 4 x 4
2. Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
3. The player can move cells with keyboard arrows
4. All the numbers should be moved in the selected direction until all empty cells are filled in
5. 2 equal cells should be merged into a doubled number
6. The merged cell can’t be merged twice during one move
7. The move is possible if at least one cell is changed after the move
8. After moving 2 or 4 appears in a random empty cell. 4 probability is 10%
9. When the 2048 value is displayed in any cell, the win message should be shown.
10. The game over message should be shown if there are no more available moves.
11. Hide the start message when the game starts.
12. Change the Start button to Restart after the first move.
13. Increase score with each move. The score should be increased by the sum of all merged cells.

# A game of 2048 was created in vanilla JavaScript, HTML and CSS.
This was a great project for practising JavaScript Array and String Methods, creating a system of coordinates, and working with DOM.

I used the following JavaScript Methods here:
querySelector(), getElementById(), push(), Math.floor(), Math.random(), innerText, parseInt(), filter(), push(), forEach(), filter(), map(), reverse(), toString(), classList, addEventListener(), removeEventListener().

Building a 2048 game using vanilla JavaScript was a great way to practice the basics of JavaScript and game programming.
