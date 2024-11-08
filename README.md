# Tic-Tac-Toe-Game
Tic Tac Toe Game in Java
The Tic Tac Toe game is a classic two-player game played on a 3x3 grid. Each player alternates marking a square on the grid with their respective symbols, "X" or "O." The objective is to place three of their marks in a row, either horizontally, vertically, or diagonally. If all nine squares are filled without a winner, the game is declared a draw.

#Components of the Game
Game Board:

The game board is represented by a 2D array, typically of size 3x3, to hold the values of each cell. Each cell can be empty, or hold an "X" or "O" depending on the player’s move.
Player:

There are two players who alternate turns. One player uses "X" and the other uses "O."
#Game Logic:

The game continues until either a player achieves three consecutive symbols (in a row, column, or diagonal), or all cells are filled resulting in a draw.
#Input/Output:

Players input the row and column for their move, which updates the board.
After each move, the game checks for a winning condition or a draw.
#Key Methods
Display Board: Displays the current state of the 3x3 grid to the players.
Player Move: Allows a player to make a move by selecting a row and column.
#Check Winner: Checks if a player has won after each move.
#Check Draw: Checks if all cells are filled and there is no winner.
Basic Java Implementation
In a Java program, these elements can be implemented within methods of a main class or separated into individual classes for better organization and modularity. Here's a brief outline of what each method does:
