Connect 4 – Unity Game Project Summary
Project Overview
This project is a 2D Connect 4 game built in Unity 6 with full support for WebGL deployment. The player can choose to compete either against another person locally or a computer-controlled AI. The project features intelligent move prediction using a Minimax algorithm with alpha-beta pruning, ensuring a challenging experience in Player vs Computer mode.
Controls
- Left-click on a column to drop your disc.
 - 'Restart' button: resets the current game.
 - 'Back to Main Menu' button: returns to the main menu.
 - On the Main Menu: choose 'Play vs Player' or 'Play vs Computer'.
Game Behaviors
- Player vs Player: Alternating turns between Red and Yellow players.
 - Player vs Computer: The AI uses Minimax with depth 3 and scoring heuristics to block, win, or control the board.
 - The game ends automatically on win or draw, with a message displayed.
 - Grid button colors dynamically update based on the current move.
 - Game supports WebGL for browser play.
Development Time & Challenges
Development took approximately 16 hours over the course of a week. The most challenging part was implementing the Minimax AI with alpha-beta pruning and ensuring it was optimized enough to run smoothly in WebGL. Another challenge was managing the board state for simulated moves without affecting the live game grid.
