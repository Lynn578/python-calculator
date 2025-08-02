# Basic Calculator

## Description
The Basic Calculator is a simple Python program that allows users to perform basic arithmetic operations including addition, subtraction, multiplication, and division. The program takes two numbers and an arithmetic operator as input from the user, then displays the calculated result.

## Features
- Supports addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
- Handles invalid operations and inputs gracefully.
- Prevents division by zero with an appropriate error message.

## How to Use
1. Run the Python script containing the calculator code.
2. When prompted, enter the first number.
3. Enter the second number.
4. Enter the operation symbol (`+`, `-`, `*`, or `/`).
5. View the result displayed on the screen.

## Example

Welcome to the Basic Calculator!
Available operations: + (addition), - (subtraction), * (multiplication), / (division)
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): *
10.0 * 5.0 = 50.0


## Requirements
- Python 3.x

## Error Handling
- If the user inputs non-numeric values for the numbers, the program will display:

Error: Please enter valid numbers.

- If the user inputs an invalid operation symbol, the program will display:
Invalid operation. Please use +, -, *, or /.

- If division by zero is attempted, the program will display:
- Error: Division by zero is not allowed.

- 
## How to Run
Run the script in the command line or any Python IDE:
python calculator.py
