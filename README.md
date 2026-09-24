Python Calculator with History
A command-line calculator program built with Python that supports basic arithmetic operations and maintains a history of all calculations.

Features
Basic Operations: Add, Subtract, Multiply, Divide

Advanced Operations: Power (^), Remainder (%)

Calculation History: View all past calculations using the ? command

Reset Function: Clear all history with the $ command

Graceful Exit: Terminate the program with the # command

Input Validation: Handles invalid number inputs gracefully

Operations

Operation	Symbol	Description

Add	+	Add two numbers

Subtract	-	Subtract second number from first

Multiply	*	Multiply two numbers

Divide	/	Divide first number by second

Power	^	Raise first number to the power of second

Remainder	%	Return remainder of division

Terminate	#	Exit the program

Reset	$	Clear calculation history

History	?	Display all past calculations

Usage
Running the Program
bash
python calculator.py
Example Session
text
Select operation.
1.Add      : + 

2.Subtract : - 

3.Multiply : * 

4.Divide   : / 

5.Power    : ^ 

6.Remainder: % 

7.Terminate: # 

8.Reset    : $ 

9.History  : ? 

Enter choice(+,-,*,/,^,%,#,$,?): +

Enter first number: 4
4
Enter second number: 3
3
4.0 + 3.0 = 7.0

Select operation.
...

Enter choice(+,-,*,/,^,%,#,$,?): ?

4.0 + 3.0 = 7.0

Project Structure

text

python-calculator/
├── calculator.py      # Main calculator program
├── README.md          # This file
├── requirements.txt   # Dependencies (if any)
└── tests/             # Test files (optional)

Requirements
Python 3.x

No external dependencies required

Code Structure
Functions
add(a, b): Returns the sum of two numbers

subtract(a, b): Returns the difference of two numbers

multiply(a, b): Returns the product of two numbers

divide(a, b): Returns the quotient of two numbers

power(a, b): Returns a raised to the power of b

remainder(a, b): Returns the remainder of a divided by b

history(): Displays all past calculations

select_op(choice): Processes user input and performs operations

Global Variables
calculation_history: List that stores all calculation strings

License
This project is open source and available for educational purposes.

Author
Created as part of a programming assignment.

Contributing
Feel free to fork this project and submit pull requests for improvements!
