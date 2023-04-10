# Snake Game
----------------------------------------------------------------------

<p>This is a simple implementation of the classic snake game in JavaScript. The game is played on a canvas element on a web page. The user controls the movement of the snake using the arrow keys on their keyboard. The objective of the game is to eat the food that appears on the canvas without colliding with the walls or the snake's own body.</p>

<h3>How to Play</h3>
<li>Clone or download this repository to your local machine</li>
<li>Open index.html in a web browser</li>
<li>Use the arrow keys to control the movement of the snake</li>
<li>Eat the food that appears on the canvas without colliding with the walls or the snake's own body</li>

<h3>Code Review</h3>

The game logic is implemented in **snake.js**. The game uses a module pattern to encapsulate its variables and functions. The module exposes an **init** function that initializes the game and starts the game loop. The game loop calls the **paint** function, which updates the state of the game and renders the canvas.

The **paint** function updates the position of the snake based on the user's input and checks for collisions with the walls, the snake's own body, and the food. If the snake collides with the walls or its own body, the game is over. If the snake collides with the food, the snake grows in size and the player's score increases.

The game uses the HTML5 canvas element to render the game. The canvas is divided into a grid of cells, and each cell represents a unit of the snake's body or the food.

