# minisweeper--js

This JavaScript code sets up the core functionality of a Minesweeper-like game

Event Listener: It listens for the DOMContentLoaded event, ensuring that the code executes after the HTML content has fully loaded.
Variables: The code initializes variables to reference essential HTML elements like the game grid, flags counter, and result message. It also stores data such as the grid width, number of bombs, an array to hold grid cells, and a flag to track game status.
createBoard Function: This function dynamically creates the game board by randomly distributing bombs and assigning numbers to non-bomb cells based on adjacent bomb counts.
click Function: Upon a cell click event, this function determines the appropriate action based on cell content. If the clicked cell contains a bomb, it triggers game over; otherwise, it reveals the cell's content and recursively uncovers adjacent empty cells.
checkSquare Function: This recursive function uncovers neighboring cells of an empty cell recursively until it encounters cells with adjacent bombs.
gameOver Function: This function handles the end-game scenario when a bomb is clicked. It reveals all bomb locations on the grid, marking the end of the game.
checkForWin Function: It checks if all bombs have been correctly flagged, signaling the player's victory.
In summary, this code implements the fundamental mechanics of a Minesweeper-style game, including bomb placement, cell revealing, flagging, and win/lose conditions, using JavaScript and DOM manipulation.

![mini sweeper](https://github.com/Saikarthik-T/minisweeper--js/assets/167961720/d2d25dd2-8e34-429a-84d4-6ddf5390d467)
