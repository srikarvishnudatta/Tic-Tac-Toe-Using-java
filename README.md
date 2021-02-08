# Tic-Tac-Toe-Using-java
Using java, a simple tic-tac-toe game is developed. This game can be played by 2 players. These players have to mention their names and choose their symbols to play the game

# System requirements:
PC with java compiler

# Description:
Using java, a simple 2 player tic-tac-toe game is developed. These players should mention their name and choose a symbol in order to play the game. As per the rules of the tic-tac-toe, the game can have only one winner among the two players or can end as draw between them. 

Implementation is as follows as; Three classes are implemented. First class named as TicTacToe which has the main function. Second, player class that is responsible for getting the player input (such as name and symbol). Third class (Board class) is the most important class, which has the game logic. The game has a board which is a 3x3 matrix. 

As the game starts (by executing the TicTacToe class), the details of the two players are requested. Players have to mention their names and pick a symbol for the game. First move is made by player-1. Now, players should make a move by mentioning the co-ordinates to place their symbol on the board. For example, if he wants to put the symbol on the top left corner, he should give the input as {0,0}. Then player-2 picks his position. If they pick a position which is out of the range (x:{0,1,2},y:{0,1,2}), that player is given another chance to pick a valid one. If any picks the position which was already picked by someone else, then that player is given another chance to pick. The games continues till a player wins. If neither of them wins, then the game ends as draw.

# Note: To start the game, run the TicTacToe.java file.
