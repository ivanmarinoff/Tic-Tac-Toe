#                       _TicTacToe_
# TicTacToe - Game Rules:
The traditional version of Tic-Tac-Toe is played on a 3×3 grid that incorporates 9 squares. 
Players game starts (either X or O) and must play the entire game using the same mark.
Players take turns, making only 1 mark with each turn.
Marks can only be placed in empty squares, and once it is placed, it is permanent.
The winner is the first player to get 3 of their marks in a straight line (the line can be positioned diagonally, vertically, or horizontally).
The game is over when all 9 squares are filled with marks, even if none of the players have a straight line of 3 marks.
If neither player has a straight line of 3 marks, it is considered a tie.

![Logo](screenshot/logo.png "TicTacToe")
# Goals
This is a simple Pygame!
The game is a part of my educational project in **_SoftUni_** course and implemented as a challenge.

# Solution 
The game uses the `PyGame` library and `random` the `randint` function.
The computer's moves are randomized, and the player chooses them himself.

# Source code link
Before start the game, import libraries `pygame` and `random`.
Then start Game form this file:
`main.py`
# Game started:
![TicTacToe](screenshot/NewGame.png "TicTacToe")

Then make your choice by typing with mouse in game screen.
If game finished with __"No Winner" :__
![NoWin](screenshot/NoWin.png "TicTacToe")
Press `Space` button to Restart the game.

If winner is player __"O" :__
![WinO](screenshot/WinO.png "TicTacToe")
Press `Space` button to Restart the game.
If winner is player __"X" :__
![WinX](screenshot/WinX.png "TicTacToe")
Press `Space` button to Restart the game.