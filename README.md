#Description

Intuition is a game implemented using the artificial intelligence AI algorithm Minimax with Alpha-beta pruning.

At each turn, the player may choose to move any number of spaces up, right, down, left, or diagonally as long as the path is not blocked by a previously visited cell.

After the first player selects a cell to start, the second player may choose a starting cell. Players then take turns moving their player to a new cell, according to the rules above, until a player can no longer make a move - meaning that the player is effectively trapped. At this point, the opposing player wins.

The AI computer player uses the Minimax algorithm. This allows the AI to take the current game board state and build a tree of all possible moves and next states that each player may take. The Minimax algorithm is then applied from the bottom of the tree, upwards, to determine the best move to make for the current turn. The AI always assumes that the player will make an optimal move, and bases its decision accordingly.

#Dependencies

This project is made using React.js.

Installing
To run this project, first of all, clone this repo and make sure you have installed node-package-manager (npm) in your system.

Open a terminal in project directory and run following commands:

Running in Development Mode
Running in Production Mode
