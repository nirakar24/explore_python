# Dictionaries
Dictionary is an unordered collection of key-value pairs. Each entry has a key and value. A dictionary can be considered as a list with special index.

The keys must be unique and immutable. So we can use strings, numbers (int or float), or tuples as keys. Values can be of any type.

Consider a case where we need to store phone numbers. We can either store them in a dictionary or a list.

## List

|Index | Numbers|          
|:------:|-----------|
|0|9920297854|
|1|7450297854|
|2|9925897854|
|3|9478297854|

## Dictionary

|Keys | Values|          
|:------:|-----------|
|Yuno|9920297854|
|Asta|7450297854|
|Yami|9925897854|
|Noelle|9478297854|

Example
```python
magic_squad = {
    "Squad":"Black Bulls",
    "Captain":"Yami Sukehiro", #Creating a Dictionary
    "rookie":"Asta"
}

print(magic_squad) #printing dictionary
print(magic_squad["Captain"]) #Printing the value of a key in dictionary
```
```
{'Squad': 'Black Bulls', 'Captain': 'Yami Sukehiro', 'rookie': 'Asta'}

Yami Sukehiro
```

### Basic Operations

Python supports various operations for creating, accessing, modifying, and iterating over dictionaries. Here are some basic operations:

- **Creating a Dictionary:**
  ```python
  # Creating a dictionary
  person = {"name": "John", "age": 30, "city": "New York"}

  # Creating an empty dictionary
  empty_dict = {}
  ```

- **Accessing Elements:**
  ```python
  # Accessing values by key
  print(person["name"])  # Output: John
  ```

- **Modifying Elements:**
  ```python
  # Modifying values
  person["age"] = 35
  print(person)  # Output: {'name': 'John', 'age': 35, 'city': 'New York'}
  ```

- **Adding Elements:**
  ```python
  # Adding new key-value pairs
  person["email"] = "john@example.com"
  print(person)  # Output: {'name': 'John', 'age': 35, 'city': 'New York', 'email': 'john@example.com'}
  ```

- **Removing Elements:**
  ```python
  # Removing key-value pairs
  del person["city"]
  print(person)  # Output: {'name': 'John', 'age': 35, 'email': 'john@example.com'}
  ```

### Additional Methods

Python provides built-in methods for performing various operations on dictionaries. Here are some commonly used methods:

- **`len()`:** Returns the number of key-value pairs in a dictionary.
- **`keys()`, `values()`, `items()`:** Returns keys, values, and key-value pairs as iterable objects.
- **`get()`:** Returns the value associated with a specified key, or a default value if the key is not found.
- **`update()`:** Updates a dictionary with the key-value pairs from another dictionary.

```python
# Length of dictionary
print(len(person))  # Output: 3

# Getting keys, values, and items
print(person.keys())    # Output: dict_keys(['name', 'age', 'email'])
print(person.values())  # Output: dict_values(['John', 35, 'john@example.com'])
print(person.items())   # Output: dict_items([('name', 'John'), ('age', 35), ('email', 'john@example.com')])
```

 [Methods in Dictionary](https://www.w3schools.com/python/python_dictionaries_methods.asp)

## Other useful links
- [W3Schools](https://www.w3schools.com/python/python_dictionaries.asp)

- [Exercise](https://www.geeksforgeeks.org/python-dictionary-exercise/)