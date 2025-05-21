# Python Assignment - Basic Arithmetic and Greeting

This repository contains two Python scripts: one that performs basic arithmetic operations and another that generates a personalized greeting.

## Table of Contents

- [Task 1: Arithmetic Operations](#task-1-arithmetic-operations)
- [Task 2: Personalized Greeting](#task-2-personalized-greeting)

## Task 1: Arithmetic Operations

### Description

This script prompts the user to enter two numbers and then performs addition, subtraction, multiplication, and division on those numbers. The results are then printed to the console.

### Usage

1.  Run the script `task1.py`.
2.  Enter the first number when prompted.
3.  Enter the second number when prompted.
4.  The script will display the results of the arithmetic operations.

### Code
a = input("Enter the First Value: ")
b = input("Enter the Second Value: ")
print("Here are the Operations",
      "\nAddition =", int(a) + int(b),
      "\nSubtraction =", int(a) - int(b),
      "\nMultiplication =", int(a) * int(b),
      "\nDivision =", int(a) / int(b))

## Task 2: Personalized Greeting

### Description

This script prompts the user to enter their first name and last name, then generates a personalized greeting message.

### Usage

1.  Run the script `task2.py`.
2.  Enter your first name when prompted.
3.  Enter your last name when prompted.
4.  The script will display a personalized greeting.

### Code

first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")
print("Hello", first_name + " " + last_name + "!", "Welcome to the python program.")
      
      
      
