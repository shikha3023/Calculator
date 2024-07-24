This project is an arithmetic calculator built using Tkinter in Python. It features a GUI (Graphical User Interface) that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. Here is a summary to understand the project easily:

Key Components:
Window Setup:

Creates a main window titled "Arithmetic Calculator."
Sets the window dimensions and background color.
Ensures the window is not resizable.
Global Variable:

equation: A string to hold the current mathematical expression.
Functions:

show(value): Appends the clicked button's value to the equation and updates the label.
clear(): Resets the equation to an empty string and updates the label.
calculate(): Evaluates the equation using the eval function and displays the result. If an error occurs, it sets the result to "error."
Display Label:

label_result: A label to show the current equation and result, configured with a specific font and size.
Buttons:

Buttons for digits (0-9), decimal point, and basic arithmetic operations (+, -, *, /).
A clear button (C) to reset the input.
An equals button (=) to evaluate the expression.
Layout:
The buttons are placed using the place method with specific coordinates for precise positioning.




Usage:
Run the script to open the calculator window.
Click the buttons to input a mathematical expression.
Click the equals button (=) to evaluate the expression and display the result.
Use the clear button (C) to reset the input and start a new calculation.
Each button is configured with properties like text, width, height, font, foreground color, background color, and a command to execute on click.
