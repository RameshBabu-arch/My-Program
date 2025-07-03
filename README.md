# My-Program
Calculator Program
# calculator.py

# Take input from user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter operation (+, -, *): ")

# Perform operation
if operation == '+':
    result = num1 + num2
    print(f"Result: {num1} + {num2} = {result}")
elif operation == '-':
    result = num1 - num2
    print(f"Result: {num1} - {num2} = {result}")
elif operation == '*':
    result = num1 * num2
    print(f"Result: {num1} * {num2} = {result}")
else:
    print("Invalid operation. Please enter +, -, or *.")
