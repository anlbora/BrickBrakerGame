# Brick Breaker Game

Brick Breaker is a classic arcade game where the player controls a paddle to bounce a ball and break bricks on the screen. The goal is to break all the bricks without letting the ball fall below the paddle.

![1](https://github.com/anlbora/BrickBrakerGame/assets/100442507/83184b3b-7a72-4a4e-b468-8624cacc0466)

## Features

- **Paddle Control:** Use the left and right arrow keys to move the paddle.
- **Brick Breaking:** Break all the bricks to win the game.
- **Score Tracking:** Earn points for each brick you break.
- **Game Over and Win Conditions:** The game ends when the ball falls below the paddle or when all bricks are broken.
- **Restart Functionality:** Press Enter to restart the game after a game over or win.

## How to Play

1. **Start the Game:**
   - Run the `Main` class to start the game.
   - The ball will start moving automatically once the game begins.

2. **Control the Paddle:**
   - Use the right arrow key (`→`) to move the paddle to the right.
   - Use the left arrow key (`←`) to move the paddle to the left.

3. **Break the Bricks:**
   - Bounce the ball off the paddle to hit and break the bricks.
   - Each broken brick adds 5 points to your score.

4. **Win the Game:**
   - Break all the bricks to win. A message will appear congratulating you.
   - Press Enter to restart the game.

   ![3](https://github.com/anlbora/BrickBrakerGame/assets/100442507/04c08221-744e-4832-a328-01997e303cda)


5. **Game Over:**
   - If the ball falls below the paddle, the game is over.
   - A message will appear showing your final score.
   - Press Enter to restart the game.
     
   ![2](https://github.com/anlbora/BrickBrakerGame/assets/100442507/0e9fdd7b-46bb-4bed-8644-d5ff459acf6c)


## Code Structure

- `Main.java`: The main class that initializes the game window and starts the game.
- `GamePlay.java`: The class that handles game mechanics, rendering, and user input.
- `MapGenerator.java`: The class that generates and manages the brick layout.
