
# Problem Solving Using Python - Beginners Bootcamp

## 1. Introduction to Python

In this section, you will be introduced to the fundamental concepts of Python programming. Here's a breakdown of the key topics:

### Python Syntax
Python syntax refers to the set of rules that define the structure of Python programs. It includes how we write commands, statements, and expressions. Python is known for its simplicity and readability, which is why the syntax focuses on reducing complexity.

- Python uses indentation to define blocks of code (no need for curly braces).
- Statements end without a semicolon.

Example:
```python
if x > 5:
    print("x is greater than 5")
```

### Variables and Data Types
Variables are used to store information to be referenced and manipulated in a program. In Python, you don't need to explicitly declare the type of the variable; it is inferred from the value you assign.

Example:
```python
x = 10  # x is an integer
name = "Alice"  # name is a string
```

#### Data Types:
Data types refer to the types of values that variables can hold. Python has several built-in data types:

- **Integer (int):** Whole numbers (e.g., `5`, `-3`)
- **Float (float):** Numbers with decimal points (e.g., `3.14`, `-0.5`)
- **String (str):** Text (e.g., `"Hello, World!"`)
- **Boolean (bool):** True or False values

### Basic Arithmetic Operations
Python supports basic arithmetic operations, allowing you to perform calculations. These include:

- **Addition (+):** Adds two numbers
- **Subtraction (-):** Subtracts one number from another
- **Multiplication (*):** Multiplies two numbers
- **Division (/):** Divides one number by another and returns a float
- **Floor Division (//):** Divides and returns the largest whole number
- **Modulus (%):** Returns the remainder of a division
- **Exponentiation (**):** Raises one number to the power of another

Example:
```python
a = 10
b = 3
print(a + b)  # Output: 13
print(a / b)  # Output: 3.3333
print(a // b)  # Output: 3 (floor division)
print(a % b)  # Output: 1 (remainder)
print(a ** b)  # Output: 1000 (10 raised to the power of 3)
```

Understanding these core concepts is essential for building more complex programs in Python.

**Notebook:** [Python Introduction](https://colab.research.google.com/github/worldbank/Python-for-Data-Science/blob/master/July_2019_Poverty_GP/day_1/1_python_intro.ipynb#scrollTo=Ko7JNLVoXExR)

---

## Beginner Hands-On Problem: Basic Python Operations

### Problem:
Write a Python script that performs the following tasks:

1. Create two variables, `a` and `b`, and assign them the values `15` and `4` respectively.
2. Print the sum, difference, product, and division of `a` and `b`.
3. Calculate and print the result of `a` raised to the power of `b`.
4. Create a variable `name` and assign it your name as a string. Print a message saying "Hello, [name]!" where `[name]` is replaced with the value of your `name` variable.
5. Convert the value of `a` to a float and print the new type of `a`.
6. Use a conditional statement to check if `a` is greater than `b`. If true, print "`a` is greater than `b`"; otherwise, print "`b` is greater than or equal to `a`".

### Example Output:
```
Sum: 19
Difference: 11
Product: 60
Division: 3.75
Power: 50625
Hello, Alice!
New type of a: <class 'float'>
a is greater than b
```

### Hints:
- Use the `type()` function to check the data type of variables.
- Use the `print()` function to display the output.

### Expected Skills to Practice:
- Working with variables
- Using basic arithmetic operators
- String manipulation
- Conditional statements
- Data type conversion

---
