# Python Calculator

A small Python project implementing addition, subtraction, multiplication, and division, with type hints, documented functions, and error handling for division by zero. Built to practice writing clear, reusable Python code.

## Features

- Addition, subtraction, multiplication, and division
- Type hints and function documentation
- Division-by-zero handling using `ValueError`

## Usage

Install Python 3.13 or later, then download or clone this repository. Create a Python file in the project folder with this example:

```python
from calculator import add, subtract, multiply, divide

print(add(10, 5))  # 15
print(subtract(10, 5))  # 5
print(multiply(10, 5))  # 50
print(divide(10, 5))  # 2.0
```

Calling `divide(10, 0)` raises `ValueError` with the message `Cannot divide by zero.`

## Running Tests

From the project folder, install pytest and run the tests:

```bash
python -m pip install pytest
python -m pytest
```