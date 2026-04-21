Overview:
Endless Runner: Obstacle Dash is a console-based game developed in C++. The objective of the game is to survive as long as possible by avoiding obstacles and collecting coins. The difficulty increases as the player progresses.

Gameplay:
The player controls a character that can move left and right, jump, crouch, and perform a long jump. Asteroids fall from the top of the screen, and the player must avoid them to prevent losing lives. Coins also appear randomly, and collecting them increases the score.
As the distance increases, the game speed becomes faster. After a certain point, an enemy is introduced to increase the challenge. The game ends when all lives are lost.

Features:
The game includes player movement, randomly generated obstacles and coins, a scoring system, and a lives system. It also provides a menu with options to start the game, view instructions, check high scores, and exit. High scores are saved using file handling.

Controls:
The player uses the keyboard to control the character. The A key moves the player left, and the D key moves right. The W key is used to jump, the S key to crouch, and the J key for a long jump. The Escape key returns to the menu.

Requirements:
The project requires a C++ compiler such as Dev C++, Code::Blocks, or Visual Studio. It is designed for Windows because it uses windows.h and conio.h libraries.

Data Storage:
The game stores high scores in a file named scores.txt. Each record includes the player’s name, score, and distance covered.

Game Logic:
The game uses a two-dimensional grid to display elements. The player, obstacles, and coins are updated continuously. Collisions with obstacles reduce lives, while collecting coins increases the score. The distance increases over time and affects the game speed.
