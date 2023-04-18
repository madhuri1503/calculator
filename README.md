# calculator
This code creates a simple calculator with a GUI that allows the user to enter arithmetic expressions and evaluate them. It uses the tkinter module to create an entry widget and buttons for each digit and arithmetic operation.
The expression is evaluated using the eval function and the result is displayed in the entry widget when the user clicks the equals button. The user can clear the expression by clicking the clear button.

STEP BY STEP DESCRIPTION


1. Import the tkinter module which provides GUI components for Python.

2.  Create a class called Calculator that inherits from the Tk class which represents the main window of the application.

3.  Define the __init__ method which initializes the calculator window and its components:
     
     a) Call the __init__ method of the Tk class to initialize the main window.
     
     b)  Set the title of the window to "Calculator".
     
     c)Set the geometry of the window to 300 pixels wide and 400 pixels tall.
     
     d) Set the window to not be resizable.
     
     e) Create a string variable called expression that will hold the expression entered by the user.
     
     f)Create an entry widget called input_field that will display the expression entered by the user.
     
     g) Set the entry widget to be disabled so the user can't directly edit it.
     
     h) Use the grid method to position the entry widget at row 0 and column 0 of the window.
     
     i) Create buttons for each digit from 0 to 9, the decimal point, and the operations +, -, *, and /.
     
     j) Use the grid method to position the buttons in a 4x4 grid starting at row 1 and column 0 of the window.
     
     k) Use the lambda function to define a function for each button that appends its respective value to the expression variable and updates the text in the
       input_field.   
     
     l) Create a button for the equals sign (=) that evaluates the expression entered by the user using the eval function and displays the result in the input_field.
     
     m) Use the grid method to position the equals button at row 5 and column 0 of the window.
     
     n) Create a button for the clear (C) function that clears the expression variable and updates the text in the input_field.
     
     o) Use the grid method to position the clear button at row 5 and column 1 of the window.

4. Create a new instance of the Calculator class and start the main event loop by calling the mainloop method of the main window.

This code creates a simple calculator with a basic user interface that allows the user to enter arithmetic expressions and evaluate them.
It uses the tkinter module to create a window with entry widgets and buttons for each digit and arithmetic operation. The user can enter an expression by clicking on the appropriate buttons and the expression is displayed in the entry widget. 
When the user clicks the equals button, the expression is evaluated using the eval function and the result is displayed in the entry widget. The user can clear the expression by clicking the clear button.
