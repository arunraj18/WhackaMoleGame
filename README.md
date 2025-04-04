# WhackaMoleGame


Whack-a-Mole Game
This project implements a simple Whack-a-Mole game with some advanced features. The game includes moles and snakes that randomly appear on the game board, a timer, and a score counter. Clicking a mole increases the score, while clicking a snake ends the game.

Features
Game Board:

A 4x3 grid of blocks where moles and snakes can appear.
Blocks display a mole or snake image when they pop up.
Score Board:

Tracks and displays the player's score.
Score increments by 1 each time a mole is clicked.
Timer:

Counts down from 30 seconds.
When the timer reaches 0, the game ends and an alert is shown.
Start Button:

Resets the game board, score, and timer when clicked.
Starts the game by initiating the mole and snake intervals.
Moles:

Appear randomly every second.
Disappear after 2 seconds if not clicked.
Up to 3 moles can be active at the same time.
Snakes:

Appear randomly every 2 seconds.
If a snake is clicked, the game ends, and snakes appear on all blocks.
All intervals are cleared when the game ends.
Files
index.html: The main HTML file that sets up the game layout.
model.js: Contains the game logic and state management.
view.js: Handles updating the UI based on the game state.
controller.js: Coordinates between the model and the view to manage game behavior.
Getting Started
Download the Project:

Download all the project files (index.html, model.js, view.js, controller.js, mole.jpg, snake.jpg).
Open the Game:

Open index.html in a web browser to start the game.
Start the Game:

Click the "Start Game!" button to begin.
The timer will start counting down from 30 seconds.
Click on moles to increase your score.
Avoid clicking on snakes to keep the game going.
