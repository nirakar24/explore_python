# Lists

Lists are one of the most versatile and commonly used data structures in Python, allowing you to store and manipulate collections of items.

## Overview

A list is a collection of items, ordered and mutable, which means you can change the content of a list after it has been created. Lists can contain elements of different data types, including numbers, strings, and even other lists.

### Basic Operations

Python supports various operations for creating, accessing, modifying, and iterating over lists. Here are some basic operations:

- **Creating a List:**
  ```python
  # Creating a list of numbers
  numbers = [1, 2, 3, 4, 5]

  # Creating a list of strings
  fruits = ["apple", "banana", "orange"]

  # Creating an empty list
  empty_list = []
  ```

- **Accessing Elements:**
  ```python
  # Accessing elements by index
  print(numbers[0])  # Output: 1
  print(fruits[-1])  # Output: orange
  ```

- **Modifying Elements:**
  ```python
  # Modifying elements
  fruits[1] = "grape"
  print(fruits)  # Output: ['apple', 'grape', 'orange']
  ```

- **Adding Elements:**
  ```python
  # Appending elements
  numbers.append(6)
  print(numbers)  # Output: [1, 2, 3, 4, 5, 6]

  # Inserting elements at a specific index
  fruits.insert(1, "kiwi")
  print(fruits)  # Output: ['apple', 'kiwi', 'grape', 'orange']
  ```

- **Removing Elements:**
  ```python
  # Removing elements by value
  numbers.remove(3)
  print(numbers)  # Output: [1, 2, 4, 5, 6]

  # Removing elements by index
  del fruits[0]
  print(fruits)  # Output: ['kiwi', 'grape', 'orange']
  ```

- **Slicing:**
  ```python
  # Slicing lists
  print(numbers[1:4])  # Output: [2, 4, 5]
  ```

### Additional Methods

Python provides built-in methods for performing various operations on lists. Here are some commonly used methods:

- **`len()`:** Returns the length of a list.
- **`append()`, `insert()`:** Adds elements to a list.
- **`remove()`, `pop()`, `del`:** Removes elements from a list.
- **`sort()`, `reverse()`:** Sorts and reverses the order of elements in a list.

```python
# Length of list
print(len(numbers))  # Output: 6

# Sorting elements
numbers.sort()
print(numbers)  # Output: [1, 2, 4, 5, 6]

# Reversing elements
numbers.reverse()
print(numbers)  # Output: [6, 5, 4, 2, 1]
```

---

This README provides an overview of basic operations, methods, and concepts related to lists in Python. It includes code examples demonstrating various operations and usage of built-in functions and methods. Feel free to explore the examples and experiment with the provided code snippets. Lists are fundamental data structures in Python, and mastering them will be beneficial in your programming journey.
## Methods in list
| Method             | Description                                                                |
| ----------------- | ------------------------------------------------------------------ |
| [append()](https://www.w3schools.com/python/ref_list_append.asp) | Adds an element at the end of the list |
| [clear()](https://www.w3schools.com/python/ref_list_clear.asp) | Removes all the elements from the list|
| [copy()](https://www.w3schools.com/python/ref_list_copy.asp) | Returns a copy of the list|
| [count()](https://www.w3schools.com/python/ref_list_count.asp)| Returns the number of elements with the specified value |
|[extend()](https://www.w3schools.com/python/ref_list_extend.asp)|Add the elements of a list (or any iterable), to the end of the current list|
|[index()](https://www.w3schools.com/python/ref_list_extend.asp)|Returns the index of the first element with the specified value|
|[insert()](https://www.w3schools.com/python/ref_list_insert.asp)|Adds an element at the specified position|
|[pop()](https://www.w3schools.com/python/ref_list_pop.asp)|Removes the element at the specified position|
|[remove()](https://www.w3schools.com/python/ref_list_remove.asp)|Removes the item with the specified value|
|[reverse()](https://www.w3schools.com/python/ref_list_reverse.asp)|Reverses the order of the list|
|[sort()](https://www.w3schools.com/python/ref_list_sort.asp)|Sorts the list|

## List Comprehension
List comprehension is basically creating lists based on other iterables such as lists, tuples, sets, and so on. It can also be described as representing for and if loops with a simpler and more appealing syntax. List comprehensions are relatively faster than for loops.

Syntax : 
```python
list = [Expression for item in iterable (if conditional)]
```
For example :
```python
list1 = [1,2,3,4,5,6,7,8,9,10]

even_list=[x for x in list1 if x%2==0] #list of even numbers in list1
print(even_list)
```
```
[2,4,6,8,10]
```

## Other useful links
- [W3Schools](https://www.w3schools.com/python/python_lists.asp)
- [Geeks for geeks](https://www.geeksforgeeks.org/python-lists/)
- [Exercise](https://www.geeksforgeeks.org/python-list-exercise/)