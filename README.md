# Python Blog

## Day 1-2: Introduction to Arrays and Strings in Python

Welcome to the Python Blog series, where we'll explore various aspects of Python programming. In the first two days, we'll dive into the fundamentals of arrays and strings.

### Day 1: Introduction to Arrays

#### What are Arrays?

In Python, an array is a collection of elements, each identified by an index or a key. Let's explore some basics:

```python
# Creating an array
my_array = [1, 2, 3, 4, 5]

# Accessing elements
print(my_array[0])  # Output: 1

# Modifying elements
my_array[1] = 10
print(my_array)  # Output: [1, 10, 3, 4, 5]

# Deleting elements
del my_array[2]
print(my_array)  # Output: [1, 10, 4, 5]


# Creating a string
my_string = "Hello, Python!"

# Accessing characters
print(my_string[0])  # Output: H

# Slicing
substring = my_string[7:13]
print(substring)  # Output: Python

# Concatenation
new_string = my_string + " Welcome!"
print(new_string)  # Output: Hello, Python! Welcome!



