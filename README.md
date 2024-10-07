# calculator-task3-
Purpose
The Simple Calculator application is a console-based program developed in Java that allows users to perform basic arithmetic operations, including addition, subtraction, multiplication, and division. This application serves as an educational tool for beginners to understand Java programming concepts, user input handling, and basic arithmetic operations.

Features
User Input:

The application prompts the user to enter two numerical values and an arithmetic operator.
Users can choose from four basic operations: addition (+), subtraction (-), multiplication (*), and division (/).
Arithmetic Operations:

Based on the operator selected by the user, the application performs the corresponding arithmetic operation.
The program can handle different combinations of operations, providing immediate results.
Error Handling:

The application checks for division by zero and invalid operators, displaying appropriate error messages when necessary.
Input validation ensures that only valid arithmetic operations are processed.
Output:

After performing the calculation, the application displays the result in a formatted manner, showing both the operation and the result.
Code Overview
Imports: The program uses the java.util.Scanner class to handle user input.

Main Method: This is the entry point of the program, where the flow of execution begins. It includes:

Initializing the Scanner object for reading input.
Prompting the user for input values and the operation to perform.
Performing the calculation based on the operator provided.
Displaying the result or an error message, as appropriate.
Switch Statement: The application employs a switch-case structure to determine which arithmetic operation to perform based on the user’s input. This ensures clear and organized handling of multiple operations.
