# Number and Strings

This folder contains examples and explanations related to numbers and strings in Python. It covers basic operations, methods, and concepts related to working with numbers and strings.

## Numbers

In Python, numbers can be represented as integers, floating-point numbers, and complex numbers. Here are some basic operations and concepts related to numbers:

- **Integer:** Whole numbers without any decimal point.
- **Float:** Numbers with decimal points or numbers written in scientific notation.
- **Complex:** Numbers with a real and imaginary part, represented as `a + bj`, where `a` is the real part, `b` is the imaginary part, and `j` is the imaginary unit.

### Basic Operations

Python supports various arithmetic operations for numbers, including addition, subtraction, multiplication, division, exponentiation, and modulus. Here are some examples:

```python
# Addition
result = 5 + 3
print(result)  # Output: 8

# Multiplication
result = 5 * 3
print(result)  # Output: 15

# Division
result = 10 / 2
print(result)  # Output: 5.0 (always returns a float)

# Exponentiation
result = 2 ** 3
print(result)  # Output: 8

# Modulus (remainder)
result = 10 % 3
print(result)  # Output: 1
```

### Additional Methods and Functions

Python provides built-in functions and methods for performing various operations on numbers. Here are some commonly used methods:

- **`abs()`:** Returns the absolute value of a number.
- **`round()`:** Rounds a floating-point number to the nearest integer.
- **`int()`, `float()`, `complex()`:** Converts a value to the specified numeric type.

```python
# Absolute value
result = abs(-10)
print(result)  # Output: 10

# Round
result = round(3.14159, 2)
print(result)  # Output: 3.14

# Conversion
result = int(3.7)
print(result)  # Output: 3
```

## Strings

Strings in Python are sequences of characters enclosed within single quotes (`'`) or double quotes (`"`). Here are some basic operations and methods related to strings:

### Basic Operations

Python supports various operations for manipulating strings, including concatenation, repetition, slicing, and indexing. Here are some examples:

```python
# Concatenation
result = "Hello, " + "World!"
print(result)  # Output: Hello, World!

# Repetition
result = "Python " * 3
print(result)  # Output: Python Python Python

# Slicing
text = "Python"
print(text[0])    # Output: P (indexing)
print(text[1:4])  # Output: yth (slicing)
```

### Additional Methods

Python provides built-in methods for performing various operations on strings. Here are some commonly used methods:

- **`len()`:** Returns the length of a string.
- **`upper()`, `lower()`:** Converts a string to uppercase or lowercase.
- **`strip()`:** Removes leading and trailing whitespace from a string.

```python
# Length of string
text = "Python"
result = len(text)
print(result)  # Output: 6

# Uppercase and lowercase
text = "Python"
result = text.upper()
print(result)  # Output: PYTHON

# Strip whitespace
text = "   Python   "
result = text.strip()
print(result)  # Output: Python
```

---

- [Methods in Strings](https://www.w3schools.com/python/python_strings_methods.asp)

## Other useful links
- [W3Schools](https://www.w3schools.com/python/python_strings.asp)
- [Exercise](https://www.geeksforgeeks.org/python-string-exercise/)