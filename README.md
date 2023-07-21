# Snake
![snake](https://github.com/buczyniak/Snake/assets/78871310/fb3618ef-1058-4d42-9ef1-18a641fdc3ad)

## Introduction to the Snake Game
The Snake Game is a classic and popular video game that has entertained players for decades. Originally developed 
in the late 1970s, the game simulates the life of a snake that continuously moves around the screen, growing longer 
as it consumes food. The player's objective is to control the snake's direction using arrow keys or other controls, 
guiding it to eat the food and avoid colliding with walls or its own tail. As the snake grows, the game becomes 
progressively more challenging, testing the player's agility and strategic thinking. The Snake Game's simplicity, 
addictive gameplay, and enduring appeal have made it a timeless favorite among gamers of all ages.

The Snake Game implementation demonstrates the principles of Object-Oriented Programming (OOP) by organizing game 
entities (snake, food, and scoreboard) into classes with attributes and methods. OOP allows for code modularity and 
easier maintenance and extension. Players can control the snake's direction using arrow keys, and the game continues 
until the snake collides with a wall or its own tail. The Snake Game provides an enjoyable and interactive gaming 
experience, challenging players to grow the snake and achieve higher scores while avoiding collisions.

The Snake was created while taking a [Udemy course](https://www.udemy.com/course/100-days-of-code/).

## Explanation of the Code

1. main.py
  The main.py script initializes the game screen using the Turtle library and sets up the Snake Game environment.
  It creates instances of the Snake, Food, and Scoreboard classes and listens for keyboard inputs to control the snake's
  movement. The game loop (while game_is_on) updates the screen, moves the snake, and checks for collisions with food,
  walls, and the snake's tail. If a collision occurs, the game ends, and the "GAME OVER" message is displayed.

3. food.py
  The food.py file contains the Food class, which represents the food object that the snake needs to eat. The food
  appears as a yellow circle on the screen and refreshes its position randomly when eaten by the snake.

5. snake.py
  The snake.py file contains the Snake class, which represents the snake controlled by the player. The snake consists
  of segments (squares), and its head leads the movement. The class contains methods to create the snake, move it, and
  control its direction (up, down, left, right). When the snake eats food, it extends by adding a new segment to its tail.

7. scoreboard.py
  The scoreboard.py file contains the Scoreboard class, responsible for keeping track of the player's score. The scoreboard
  displays the current score on the top of the screen. When the snake eats food, the score increases, and the scoreboard
  is updated. If the snake collides with a wall or its own tail, the "GAME OVER" message is displayed.
