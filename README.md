# LAB - Class 42

## Project: pythonisms

## Author: Eric Mungai Kinuthia

## About

This project demonstrates pythonic language features using a MyCollection class, a basic collection class that allows you to store and manipulate data.

The MyCollection class includes the following methods:

1. `__str__(self)`: Returns a string representation of the data in the collection.
2.` __iter__(self)`: Defines the iterator for the class, which is a generator that yields each value in the data.
to_list(self): Converts the collection to a list by creating a new list from the iterator.
3. `__len__(self)`: Returns the length of the data.
4. `__getitem__(self, index)`: Returns the value at the specified index in the data list.
5. `__contains__(self, value)`: Checks if the specified value is in the data.
6. `__reversed__(self)`: Returns a new MyCollection object that contains the data in reverse.

## Contributors

Adam Owada, Chat gpt

## Tests

[Links to Test](/tests/test_pythonism.py)

[Link to Test](/tests/test_linked_list.py)



