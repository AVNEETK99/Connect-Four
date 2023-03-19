# Connect-Four

The goal of the Connect Four game project is to implement the classic board game using Python and the Pygame library. The objective of the game is for two players to take turns dropping colored discs, red and yellow, into a 6x7 grid. The first player to connect four of their colored discs either vertically, horizontally, or diagonally wins the game.

The project aims to provide an interactive game experience for users and demonstrate the use of the Pygame library for game development. It also involves the use of programming concepts such as functions, loops, and conditional statements to implement the game logic.

## Instructions to run the game

* Go to the repository on GitHub: https://github.com/AVNEETK99/connect-four
* Click on the green "Code" button and select "Download ZIP" to download the code to your computer.
* Extract the downloaded ZIP file to a folder on your computer.
* Open a command prompt or terminal window and navigate to the directory where you extracted the code.
* Install the required dependencies by running the command: pip install -r requirements.txt
* Run the game by running the command: ```python connect_four.py```
* The game window should appear and you can play the game using your mouse.

## Functionality of the code

* The code starts by importing the necessary Pygame library and initializing some constants, including the colors for the game pieces, the size of the game board, and the number of rows and columns.

* It then defines several functions to handle various aspects of the game, including creating the game board, dropping pieces onto the board, checking if a given location on the board is valid, getting the next available row to drop a piece, printing the board, checking if a given move is a winning move, and drawing the game board.

* After defining these functions, the code creates the game board, initializes Pygame, sets the screen size, and draws the initial game board.

* The code then enters a loop where it waits for user input, either by moving the mouse over the screen or clicking the mouse.

* When the mouse is moved, the code displays the appropriate colored disc on the top of the screen to indicate where the next piece will be dropped.

* When the mouse is clicked, the code drops the appropriate colored disc into the grid, checks if the move is a winning move, and displays a message indicating which player has won the game.

* The loop continues until the game is over, at which point it exits.
