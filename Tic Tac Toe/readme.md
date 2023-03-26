# Introduction

Tic Tac Toe is a classic paper-and-pencil game often played between two players. The game is straightforward and requires little setup. In this project, I will present a graphical Tic Tac Toe game that allows users to play the game against the computer. The game's interface is user-friendly, and the computer's algorithm ensures the game is challenging and fun.

# Basic Functionalities

The graphical Tic Tac Toe game consists of a 3x3 grid. The game begins with an empty grid, and players take turns placing their mark (X or O) in an empty square. The player who places three of their marks in a row, column, or diagonal wins the game. If all squares are filled and no player has three marks in a row, the game ends in a draw.

# Instructions

- Launch the game by running the Python script.
- The game board will appear in a new window.
- The game begins with Player 1 (X) making the first move. Click on an empty square to place an X in that square.
- The computer will make its move (O). Wait for the computer's move before making your next move.
- Play continues in this alternating fashion until one player gets three in a row or all squares are filled.
- If one player gets three in a row, a message will appear declaring that player as the winner.
- If all squares are filled and no player has three in a row, a message will appear declaring a draw.
- To play again, close the game window and relaunch the game.

# Unique Features

In addition to the basic functionalities of Tic Tac Toe, this game has several unique features that enhance the user's experience: 

- User-friendly interface: The game's interface is simple and intuitive, making it easy for users to understand and play.

- Intelligent computer opponent: The game's computer opponent uses a smart algorithm to determine its moves. The computer evaluates each possible move and selects the one that will give it the best chance of winning.

- Customizable player names: Players can enter their names before starting the game, adding a personal touch to the game.

# Thought Process

The development of this game involved several steps. The first step was to create the graphical interface for the game using the tkinter module. I created a 3x3 grid of buttons that users could click to place their marks.

The second step was to develop the game logic. I created a class called TicTacToe that contained methods for checking if a player had won, if the game had ended in a draw, and for resetting the game board.

The third step was to create the computer opponent. I developed an algorithm that evaluated each possible move and selected the one that would give the computer the best chance of winning.

The final step was to add unique features to the game, such as the customizable player names and user-friendly interface.

# Challenges Faced and Overcoming Them

One of the main challenges I faced was developing the computer opponent. I had to find a way to create an algorithm that was both smart and efficient. After several iterations, I developed an algorithm that evaluated each possible move and selected the one that would give the computer the best chance of winning.

Another challenge was creating the game logic to detect if a player had won or if the game had ended in a draw. I had to carefully consider all possible winning combinations and create an efficient algorithm that could detect them.

# Conclusion
The graphical Tic Tac Toe game is a fun and challenging game that provides users with an enjoyable experience. The game's user-friendly interface, intelligent computer opponent, and customizable player names add to the game's appeal.
