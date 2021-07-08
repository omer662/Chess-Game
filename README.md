# Two Player Chess Game
This is a two-player chess game I made using python (and the pygame library), built using pycharm.

The game is devided to classes:
  Game - The class that contains the function that checks if the game is over, and the data of both players.
  Player - The class that saves data about a player - team color, player name, additional data about the player, and a list of the player's tools.
  Tool - The parent class for all the tools' classes, contains basic functions for all types of tools.
  Pawn, Rook, Bishop, Queen, King, Knight - The classes for specific tool types, contains functions that work differently for each tool type (like check if move to a certain         position on the board is valid.

The program runs once per game - a tie / win / closing the game window would mean you need to run it again. Info about illegal moves / game-end messages are printed to the console. To run the game - unzip the project into one folder (no need to move anything), and run the main.py file
