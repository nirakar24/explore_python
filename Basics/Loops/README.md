# Loops

Loops are used to execute a block of code repeatedly, either a fixed number of times or until a certain condition is met.

## Overview

Loops are essential constructs in programming that allow you to iterate over collections of data, perform repetitive tasks, and control the flow of execution. In Python, loops are implemented using the `for` and `while` loops.

### `for` Loop

The `for` loop is used to iterate over a sequence (such as a list, tuple, or string) or any iterable object. It executes a block of code for each item in the sequence.

#### Syntax

```python
for item in sequence:
    # Block of code to execute for each item
```

#### Example

```python
# Example of a for loop
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

### `while` Loop

The `while` loop is used to execute a block of code repeatedly as long as a specified condition is true. It continues iterating until the condition becomes false.

#### Syntax

```python
while condition:
    # Block of code to execute while the condition is true
```

#### Example

```python
# Example of a while loop
x = 0

while x < 5:
    print(x)
    x += 1
```

### Control Statements

Python provides control statements such as `break`, `continue`, and `pass` to modify the behavior of loops.

- **`break`**: Terminates the loop prematurely.
- **`continue`**: Skips the rest of the current iteration and continues with the next iteration.
- **`pass`**: Acts as a placeholder and does nothing.

#### Example

```python
# Example of control statements in a loop
for i in range(10):
    if i == 3:
        continue  # Skip iteration if i equals 3
    elif i == 7:
        break  # Exit loop if i equals 7
    else:
        pass  # Do nothing
    print(i)
```

---

