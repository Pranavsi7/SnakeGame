# SnakeGame
Snake game in Java using Gui
A classic Snake Game implemented using Java and Swing for the graphical user interface (GUI). In this game, the player controls a snake that moves around the screen, eats food to grow longer, and avoids collisions with the walls or itself.

Features
1.Graphical User Interface (GUI): The game uses Java Swing to display the snake, food, and game grid.
2.Smooth Gameplay: The snake glides smoothly, and you have to control it with arrow keys on your keyboard.
3.Growing Difficulty: Every time the snake eats food, it will grow long and the speed of the game will increase.
4.Keeping Score: Your score appears at the top of the game screen and it increases every time you consume the food item.
 How to Play
1.Use the Arrow keys (Up, Down, Left, Right) for controlling the direction of the snake.
2.Objective :To eat food that appears on the screen and is represented by a little square.
3.Each time that the snake eats, it will grow longer.
4.If the snake collides with the wall or to itself, then the game is finished.
5.The score is printed at the top of the screen, indicating the number of food pieces the snake has eaten.



![Screenshot 2024-12-05 191425](https://github.com/user-attachments/assets/824fa40d-dbfe-484f-b3ac-28faf83b5d5a)





Kew Components
Here are the key components of GamePanel:

Constants for game settings:
1.We define constants like screen size, unit size (for both the snake parts and apples), and the game speed (delay).
2.Game variables: These include the x and y coordinates for all parts of the snake, the score (apples eaten), and flags for the game state (running or not).
3.A timer: This triggers actions at a constant interval, essential for game animation.
4.Starting the snake game: The startGame method initializes the game by spawning the first apple, starting the timer, and setting the game state to running.

Initialization
In its constructor, it initializes the game with a new apple, sets up the game dimensions, background color, and key listeners.

Drawing on the panel
The draw method handles rendering the snake, the apple, and the score. It changes colors for different parts of the snake and displays the score on the screen. If the snake game is not running, it calls gameOver to display the end game message.

Game logic
This includes moving the snake, checking for apples, and checking for collisions. The snake moves by updating the positions of its parts. Eating an apple increases the snake’s length and the score. Collisions with the wall or the snake itself stop the game.




![image](https://github.com/user-attachments/assets/2d9bea7a-2920-44a3-a4b4-187d2445b54f)






Conclusion
This code provides a complete setup for a Snake game y8. It demonstrates how to set up a GUI application, handle user input, and implement game logic in Java. Whether you’re new to programming or looking to refresh your Java skills, building this game is a fun and educational project that covers many fundamental concepts.

