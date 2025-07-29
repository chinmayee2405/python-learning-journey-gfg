# Python Introduction

## Definition:
Python is a high-level, interpreted, general-purpose programming language. It is known for its simplicity and readability, making it an excellent choice for beginners.
Created by **Guido van Rossum** and released in **1991**, Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

## Features:
- Easy to learn and read
- Dynamically typed
- Interpreted language (no compilation required)
- Portable (runs on many platforms)
- Large standard library
- Supports multiple programming paradigms (OOP, functional, procedural)

## Example:
```python
print("Hello, Python!")
```
#### ✅ Output:
```python
print("Hello, Python!")
```

---

### 💻 `2_input_output.py`


# Input and Output in Python

# Definition:
- input(): Used to take user input (returns a string)
- print(): Used to display output on the screen

# Rules:
 - input() always returns a string. Convert it using int(), float() if needed.
 - print() can output text, variables, or expressions.

# Examples:
 Taking input from the user
 ```
name = input("Enter your name: ")
age = int(input("Enter your age: "))
height = float(input("Enter your height in meters: "))
```
# Output using print()
```
print("Hello,", name)
print("You are", age, "years old.")
print("Your height is", height, "meters.")
```
# Output formatting
```
print(f"{name} is {age} years old and {height} meters tall.")
```
## Comments in Python

# Definition:
 Comments are lines in the code that are not executed by Python. They help explain the code.

## Types:
- Single-line comments: start with '#'
 - Multi-line comments: enclosed in triple quotes (''' or """)

# Example:
```
# This is a single-line comment
print("Hello")  # This is an inline comment
```
```
This is a multi-line comment
that spans across multiple lines.
Used for documentation or explanations.
```
# Output:
```# Hello
```
## Python Variables

# Definition:
- Variables are containers for storing data values.
- You do not need to declare variables before using them.

## Rules for Naming Variables:
 - Must start with a letter (a–z, A–Z) or underscore (_)
 - Cannot start with a number
 - Can contain letters, numbers, and underscores
 - Case-sensitive (name and Name are different)
 - Should not use Python keywords

## Examples:
```
x = 5                # Integer
name = "Alice"       # String
pi = 3.14            # Float
is_active = True     # Boolean

print(x)
print(name)
print(pi)
print(is_active)
```
# Reassignment
```
x = "Now a string"
print(x)

```
# Keywords in Python

# Definition:
 Keywords are reserved words in Python that have special meaning.
 They cannot be used as variable, function, or class names.
```
import keyword

# Display all keywords
print("List of Python Keywords:")
print(keyword.kwlist)
```
## Rules:
- Cannot use keywords as variable names
 - Using a keyword as a variable will raise a SyntaxError

``` ❌ Invalid
# for = 5
# print(for)  # SyntaxError
```
## Example of valid vs invalid
```x = 10           # Valid
# def = 20       # Invalid, 'def' is a keyword
```
## Categories of Keywords:
 - Value Keywords: True, False, None
 - Operator Keywords: and, or, not, is, in
 - Control Flow: if, else, elif, for, while, break, continue, pass, try, except, finally, raise, assert
 - Function & Class: def, return, lambda, yield, class
 - Context Management: with, as
 - Import: import, from
 - Scope: global, nonlocal
 - Async: async, await
