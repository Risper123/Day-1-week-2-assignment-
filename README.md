# Day-1-week-2-assignment-
Assignment for day -1 week 2
Basic Calculator Program

Create a simple Python program that asks the user to input two numbers and a mathematical operation (addition, subtraction, multiplication, or division).
Perform the operation based on the user's input and print the result.
Example: If a user inputs 10, 5, and +, your program should display 10 + 5 = 15.
Here’s a shorter and simpler version of the program:

# Simple calculator
num1 = float(input("Enter the first number: 10"))
num2 = float(input("Enter the second number:5 "))
operation = input("Enter the operation (+, -, *, /): ")

if operation == '+':
    print(f"{num1} + {num2} = {num1 + num2}")
elif operation == '-':
    print(f"{num1} - {num2} = {num1 - num2}")
elif operation == '*':
    print(f"{num1} * {num2} = {num1 * num2}")
elif operation == '/':
    print(f"{num1} / {num2} = {num1 / num2}" if num2 != 0 else "Error: Division by zero is not allowed.")
else:
    print("Invalid operation.")



