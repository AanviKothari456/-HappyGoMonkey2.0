# HappyGoMonkey2.0

This is a simple endless runner game called "Monkey Runner". The objective of the game is to help the monkey collect bananas while avoiding obstacles.

Game Components:
Monkey: The main character of the game. It can move up and down and collects bananas.
Banana: The collectible item in the game. The monkey earns points by collecting bananas.
Obstacle: The obstacles that the monkey needs to avoid. If the monkey touches an obstacle, the game ends.
Ground: The platform on which the monkey and obstacles move.

Game Rules:
The monkey automatically moves forward.
Press the spacebar to make the monkey jump.
Avoid touching the obstacles.
Collect as many bananas as possible to increase your score and survival time.
The game ends if the monkey touches an obstacle.
Instructions to Play:
Use the spacebar to make the monkey jump.
Collect bananas to increase your score.
Avoid touching the obstacles.
Survive as long as possible to achieve a high score.
Technical Details:
The game is built using the p5.js library, a JavaScript library for creative coding.
The game window size is 400x400 pixels.
The game loop runs at 60 frames per second.
The ground moves from right to left to create the illusion of the monkey running.
The survival time increases with each frame, and it represents the player's score.
The game ends when the monkey touches an obstacle.
The game assets, such as images for the monkey, banana, and obstacle, are preloaded using the preload function.
The draw function is called repeatedly and handles the game logic and rendering.
The spawnBanana function creates bananas at regular intervals.
The spawnObstacles function creates obstacles at regular intervals.
Controls:
Spacebar: Jump
