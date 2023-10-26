# Calculator-Application
This is a simple calculator program built in Java with a graphical user interface (GUI).

This is a simple calculator program built in Java with a graphical user interface (GUI). Here's a quick explanation of the code:

import statements: These lines tell the program to use pre-made code (libraries) to create windows, buttons, text fields, etc.

CalculatorApp class: This is where the main code for the calculator is written.

private variables:

display: A text field where numbers and results are shown. It can't be edited directly.
buttons: An array to hold all the buttons.
buttonLabels: An array of strings representing the labels for the buttons.
input: A string to store the user's input (numbers and operators).
num1, num2: Variables to store the numbers for calculations.
operator: A variable to store the current operation (+, -, *, /).
CalculatorApp() method:

It's a special method (constructor) that runs when a new CalculatorApp object is created.
It sets up the calculator's user interface (UI):
A text field at the top for displaying numbers and results.
An array of buttons arranged in a 4x4 grid for numbers and operations.
The UI is organized using panels and layouts.
actionPerformed(ActionEvent e) method:

This method is called whenever a button is clicked.
It figures out which button was clicked and takes appropriate action:
If it's a number or operator button, it updates the input.
If it's the "=" button, it calculates the result.
If it's the "C" button, it clears the display.
appendToDisplay(String text) method:

This method appends the clicked button's label to the input.
setOperator(char op) method:

This method sets the operator for the calculation and stores the first number (num1).
calculateResult() method:

This method performs the actual calculation based on the stored operator and the second number (num2).
clearDisplay() method:

This method clears the display and resets the input.
main(String[] args) method:

This is where the program starts running.
It creates a new instance of CalculatorApp which displays the calculator window.
setTitle, setSize, setDefaultCloseOperation, setLocationRelativeTo, setVisible:
These are methods used to configure the appearance and behavior of the calculator window.
Overall, this program creates a functional calculator with a user-friendly graphical interface. Users can click buttons to perform calculations, and the result is displayed in the text field.




