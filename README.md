# Breakout Game
**Breakout** game built in Python using Pygame library. Control the paddle, bounce the ball, and destroy all the blocks to win

---

## Features

- 🎨 **Color-coded Blocks**: Blue (3 hits), Green (2 hits), and Red (1 hit).
- 🕹️ **Simple Controls**: Move the paddle to prevent the ball from falling.
- 🎮 **Winning/Losing States**: Destroy all blocks to win or let the ball fall to lose.
- 💡 **Dynamic Gameplay**: Ball speed adjusts based on collisions.

---

## Controls

| **Action**      | **Key**              |
|------------------|----------------------|
| Move Left        | Left Arrow Key       |
| Move Right       | Right Arrow Key      |
| Start Game       | Click Anywhere       |

## Game Flow

1. Start Screen:
   - When the game loads, instructions are displayed:
     "Use arrow keys to move"
     "CLICK ANYWHERE TO START"

2. Gameplay:
   - The player controls the paddle to keep the ball bouncing.
   - The ball destroys blocks upon collision.
   - Blocks have different strengths, requiring multiple hits to destroy some.
   - If all blocks are destroyed, the player wins.
   - If the ball falls below the paddle, the player loses.

3. Win Screen:
   - Displays "YOU WON!" when all blocks are destroyed.
   - Prompt: "CLICK ANYWHERE TO START" to restart.

4. Lose Screen:
   - Displays "YOU LOST!" when the ball falls below the paddle.
   - Prompt: "CLICK ANYWHERE TO START" to restart.
