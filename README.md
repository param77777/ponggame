# Pong Game 🎮

This is a recreation of the classic **Pong** game using Python's `turtle` library. It is a two-player game where players control paddles to keep the ball in play and score points against their opponent.

## Features
- **Two-Player Gameplay**: Compete against a friend using keyboard controls.
- **Dynamic Ball Speed**: The ball speed increases with each successful hit.
- **Score Tracking**: Displays scores for both players.
- **Responsive Paddles**: Smooth paddle movement with keyboard controls.

## Prerequisites
Ensure you have Python installed on your system. The following modules are used in the game:
- `turtle`
- `time`

## Controls
### Right Paddle (Player 1):
- **Up Arrow**: Move paddle up
- **Down Arrow**: Move paddle down

### Left Paddle (Player 2):
- **W**: Move paddle up
- **S**: Move paddle down

## How to Play
1. Each player uses their respective controls to move the paddles.
2. The goal is to hit the ball and prevent it from going past your paddle.
3. If the ball passes your paddle, the opposing player scores a point.
4. The first player to reach the winning score (default is unlimited) wins the game!

## Files in the Project
- **main.py**: The main script to run the game.
- **paddle.py**: Contains the `Paddle` class to handle paddle movement.
- **ball.py**: Contains the `Ball` class to manage ball movement, collision, and speed.
- **scoreboard.py**: Contains the `Scoreboard` class to track and display scores.

## How It Works
### Ball Movement:
- The ball moves continuously in both X and Y directions.
- It bounces off the top and bottom walls.

### Paddle Interaction:
- Players use the keyboard controls to move their paddles and deflect the ball.

### Scoring:
- If the ball crosses the right boundary, Player 2 scores.
- If the ball crosses the left boundary, Player 1 scores.

### Game Restart:
- The ball resets its position and speed after a player scores.

## Future Improvements
- Add difficulty levels.
- Introduce sound effects.
- Implement AI for single-player mode.
- Add customizable themes.

## Author
Created by **Tallapalli Parameswara Reddy**.
