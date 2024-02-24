# Snake (Java)

How to code a snake game in Java for beginners! Learn how to create a game of snake in Java using the awt and swing graphics library. Here I learn how to create a graphical user interface (GUI) to display the Snake game, create the game loop, listen for Key presses to move the snake, use the ArrayList to store the snake's segments, and check collision and out of bounds for game over.


## Some new function we add.
 In future if I continue working on this project One feature we can add is a keyListener in KeyPressed to restart the game every time there is a game over. ex) if (e.getKeyCode() == KeyEvent.VK_SPACE && gameOver). Inside this conditional statement, we should reset the game to default (clear snakeBody ArrayList, call placeFood(), etc). Another feature we can add after this is keep track of the high score and paint it below the current score. For this we will need a variable to keep track of high score.
