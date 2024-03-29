# Pong Game

## Description
This is a simple implementation of the classic Pong game using Python's Turtle module. The game features two paddles controlled by the players and a ball that bounces around the screen. Players score points when the ball passes their opponent's paddle.

## Features
- Two paddles, one for each player, which can be controlled using the arrow keys and 'W' and 'S' keys.
- A ball that bounces off the paddles and walls.
- Score tracking for each player.
- The game ends when one player reaches a certain score limit (not implemented yet).

## Files
1. **main.py:** This file contains the main game loop and initializes the game components.
2. **paddle.py:** Defines the Paddle class which creates the paddles for the players.
3. **ball.py:** Defines the Ball class which creates the ball object and handles its movement.
4. **scoreboard.py:** Defines the Scoreboard class which keeps track of the score for each player.
5. **README.md:** This file provides information about the game, its features, and how to run it.

## How to Run
To run the game, ensure you have Python installed on your system along with the Turtle module. Execute the `main.py` file using a Python interpreter. The game window will appear, and you can start playing by using the specified keys for paddle movement.

## Controls
- Player 1 (Right Paddle):
  - Up Arrow: Move paddle up
  - Down Arrow: Move paddle down
- Player 2 (Left Paddle):
  - 'W' Key: Move paddle up
  - 'S' Key: Move paddle down

## Dependencies
- Python 3.x
- Turtle module (comes pre-installed with Python)

## Note
This implementation is a basic version of Pong and can be further extended with additional features such as sound effects, better graphics, and advanced AI opponents. Feel free to fork and modify the code according to your requirements.
