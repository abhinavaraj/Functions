# Functions # Functions in Python 🛠️🐍

This repository contains notes and examples on **Functions** in Python.  
Functions are reusable blocks of code that make programs modular, readable, and efficient.  

---

## 🚀 About the Project
- A **function** is defined using the `def` keyword.  
- Functions help avoid code duplication and improve clarity.  
- Python also supports **built-in functions**, **user-defined functions**, **lambda functions**, and **recursive functions**.  

---

## 📂 Repository Structure
├── basic_functions.py # Defining and calling functions
├── arguments.py # Positional, keyword, default, variable arguments
├── lambda_functions.py # Anonymous functions
├── recursion.py # Recursive functions
└── README.md

yaml
Copy code

---

## 📖 Topics Covered

### 🔹 Defining a Function
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))
🔹 Function Arguments
✅ Default Arguments
python
Copy code
def power(base, exp=2):
    return base ** exp

print(power(3))    # 9
print(power(3, 3)) # 27
✅ Keyword Arguments
python
Copy code
def student(name, age):
    print(f"Name: {name}, Age: {age}")

student(age=20, name="Bob")
✅ Variable-Length Arguments
python
Copy code
def add_all(*numbers):
    return sum(numbers)

print(add_all(1, 2, 3, 4))   # 10
🔹 Lambda Functions
Anonymous, one-line functions.

python
Copy code
square = lambda x: x * x
print(square(5))   # 25
🔹 Recursive Functions
A function that calls itself.

python
Copy code
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n-1)

print(factorial(5))  # 120
🛠️ Installation
Make sure you have Python installed (>=3.8).

Run the examples directly:

bash
Copy code
python basic_functions.py
python arguments.py
python lambda_functions.py
python recursion.py
🎯 Learning Resources
Python Official Docs – Functions

W3Schools – Python Functions

