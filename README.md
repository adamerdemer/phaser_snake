# Phaser Snake Game

Phaser games are organized around states. Think of states in Phaser as the different parts of a game. Here are the states of this game:

- The **Menu** state. It is handled by **menu.js**, and only displays the start image. When it is clicked, the game transitions to the **Game** state.
- **Game** state. It is handled by game.js. This is the actual play area of the game. You control the snake, eat apples and have lots of fun. When you die, you transition to the **Game_Over** state.
- **Game_Over** state. It shows gameover.png and displays your last score. When it is clicked you transition to the **Game** state.

**main.js** is this main JavaScript file. This is the place where we will create a new game instance and add a menu state.

![How to calculate game speed based on score](http://imgur.com/lV4zg2m)