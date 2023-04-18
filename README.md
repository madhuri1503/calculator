# calculator
This code creates a simple calculator with a GUI that allows the user to enter arithmetic expressions and evaluate them. It uses the tkinter module to create an entry widget and buttons for each digit and arithmetic operation.
The expression is evaluated using the eval function and the result is displayed in the entry widget when the user clicks the equals button. The user can clear the expression by clicking the clear button.

STEP BY STEP DESCRIPTION

a) Import the tkinter module which provides GUI components for Python.
b) Create a class called Calculator that inherits from the Tk class which represents the main window of the application.
c) Define the __init__ method which initializes the calculator window and its components:
     * Call the __init__ method of the Tk class to initialize the main window.
     * Set the title of the window to "Calculator".
     * Set the geometry of the window to 300 pixels wide and 400 pixels tall.
     * Set the window to not be resizable.
     * Create a string variable called expression that will hold the expression entered by the user.
     * Create an entry widget called input_field that will display the expression entered by the user.
     * Set the entry widget to be disabled so the user can't directly edit it.
     * Use the grid method to position the entry widget at row 0 and column 0 of the window.
     * Create buttons for each digit from 0 to 9, the decimal point, and the operations +, -, *, and /.
     * Use the grid method to position the buttons in a 4x4 grid starting at row 1 and column 0 of the window.
     * Use the lambda function to define a function for each button that appends its respective value to the expression variable and updates the text in the input_field.
     * Create a button for the equals sign (=) that evaluates the expression entered by the user using the eval function and displays the result in the input_field.
     * Use the grid method to position the equals button at row 5 and column 0 of the window.
     * Create a button for the clear (C) function that clears the expression variable and updates the text in the input_field.
     * Use the grid method to position the clear button at row 5 and column 1 of the window.
d) Create a new instance of the Calculator class and start the main event loop by calling the mainloop method of the main window.

This code creates a simple calculator with a basic user interface that allows the user to enter arithmetic expressions and evaluate them.
It uses the tkinter module to create a window with entry widgets and buttons for each digit and arithmetic operation. The user can enter an expression by clicking on the appropriate buttons and the expression is displayed in the entry widget. 
When the user clicks the equals button, the expression is evaluated using the eval function and the result is displayed in the entry widget. The user can clear the expression by clicking the clear button.
