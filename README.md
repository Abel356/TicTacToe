# TicTacToe
This JavaScript project implements a simple, interactive Tic-Tac-Toe game. The primary goal is to provide a fun, engaging way for two players to compete in a classic game of Tic-Tac-Toe directly in their web browser. Below is a detailed description of the key components and functionality of the project:

1. **Constants and Initial Setup**
**CSS Class Constants**: The project defines two constants, X_CLASS and CIRCLE_CLASS, which represent the CSS classes used to mark cells with X and O, respectively.
**Winning Combinations**: An array, WINNING_COMBINATIONS, lists all possible winning line combinations for the Tic-Tac-Toe board.
2. **DOM Elements**
**Cell Elements**: The cellElements constant retrieves all cell elements in the game board.
**Board Element**: The board constant references the game board element.
**Winning Message Elements**: The winningMessageElement and winningMessageTextElement constants are used to display the game's winning or draw message.
**Restart Button**: The restartButton constant references the button used to restart the game.
3. **Game Initialization**
**Starting the Game**: The startGame function initializes the game by resetting the board, clearing any previous marks, and setting up event listeners for each cell. It also removes any displayed winning messages.
Event Listener for Restart Button: An event listener on the restartButton triggers the startGame function to reset and restart the game when clicked.
4. **Handling Click Events**
**Handling Click**s: The handleClick function is called whenever a cell is clicked. It determines the current player's mark (X or O), places the mark, checks for a win or draw, and then either ends the game or switches turns.
5. **Game Ending and Checking Conditions**
**Ending the Game**: The endGame function displays a message indicating whether the game ended in a draw or a win.
**Checking for Draw**: The isDraw function checks if all cells are filled without any player winning, indicating a draw.
**Placing a Mark**: The placeMark function adds the appropriate CSS class (X or O) to the clicked cell.
**Swapping Turns**: The swapTurns function toggles the turn between X and O.
**Setting Board Hover Class**: The setBoardHoverClass function changes the board’s hover state to reflect the current player’s mark.
**Checking for Win**: The checkWin function checks if the current player has achieved any of the winning combinations.
This code ensures a smooth and interactive gaming experience, allowing two players to enjoy a competitive game of Tic-Tac-Toe with visual feedback and a simple user interface.
