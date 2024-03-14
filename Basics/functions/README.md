# Functions

Functions are blocks of reusable code that perform a specific task. They allow you to modularize your code, improve readability, and avoid repetition.

## Overview

Functions play a crucial role in Python programming, enabling you to break down complex tasks into smaller, manageable units. They promote code reusability and maintainability by encapsulating logic within named blocks.

### Defining Functions

In Python, you can define a function using the `def` keyword, followed by the function name and parentheses containing optional parameters. A function may return a value using the `return` statement.

#### Syntax

```python
def function_name(parameters):
    # Block of code to execute
    return value  # Optional
```

### Example

```python
# Example of a simple function
def greet(name):
    return f"Hello, {name}!"

# Calling the function
message = greet("John")
print(message)  # Output: Hello, John!
```

### Parameters and Arguments

Functions can accept parameters, which are variables passed to the function, and arguments, which are values supplied when calling the function.

#### Example

```python
# Example of a function with parameters
def add(a, b):
    return a + b

# Calling the function with arguments
result = add(3, 5)
print(result)  # Output: 8
```

### Default Parameters

Python allows you to specify default values for parameters. If an argument is not provided when calling the function, the default value is used.

#### Example

```python
# Example of default parameters
def greet(name="Guest"):
    return f"Hello, {name}!"

# Calling the function without providing an argument
message = greet()
print(message)  # Output: Hello, Guest!
```

### Variable-Length Arguments

Functions can accept a variable number of arguments using special syntax `*args` and `**kwargs`, which represent variable-length positional and keyword arguments, respectively.

#### Example

```python
# Example of variable-length arguments
def calculate_sum(*args):
    return sum(args)

# Calling the function with multiple arguments
result = calculate_sum(1, 2, 3, 4, 5)
print(result)  # Output: 15
```

---

## Types of functions

### There are 2 types of Functions: 

1. **Built-in Functions**: These are functions that come pre-installed with your Python installation. You just need to call the functions with the necessary parameters to get the desired output. For example, [`print()`](https://www.w3schools.com/python/python_ref_functions.asp) is nothing but a function which we can call anywhere.

2. **User Defined Function**: These are the functions which one can create on their own. But keep in mind that to declare a function you have to use `def` + `any_name` + `:` and all the lines of code in those functions should follow an indentation. 

For example:

```python
def add(x, y):
    return x + y
```
Now we have our simple function named add , here x and y are the parameters .Parameters are the variables that are placeholders for the values that will be passed into the function when it is called. These values are called __arguments__.
 
`return x+y` would return the additon and will exit the function 

we can call the function like
```python
result = add(3,4)
print(result)
```
and also as 

```print(add(3,4))```
