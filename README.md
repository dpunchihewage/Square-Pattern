# Square-Pattern

This code uses the PyAutoGUI library to draw a grid of squares on the screen. The draw_square() function takes three arguments: the x and y coordinates of the top-left corner of the square, and the size of the square.

The for loop in the main body of the code iterates over 30 rows and 10 columns of squares, and calls draw_square() with the appropriate coordinates for each square. The x and y coordinates of each square are offset by multiples of 60, and the size of each square is fixed at 50.

The pyautogui library provides functions for controlling the mouse and keyboard to automate tasks on the computer. In this code, pyautogui.moveTo() and pyautogui.dragTo() functions are used to move the mouse to the desired location and draw lines to create the squares.
