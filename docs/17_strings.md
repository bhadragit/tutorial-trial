# Chapter 17 - Strings 
time duration: 37:51 - 43:20  
### String Declaration

- Text in Python should be enclosed in quotes — single (' ') or double (" "); both work, but double quotes are more commonly used.

- Triple quotes (''' ''' or """ """) are used for multi-line strings, like email messages or formatted text blocks.
```python
# 17_strings.py
message = """
Hi John, 

This is mosh from codewithmosh


blah blahh balhh...
"""
```

### Getting String Length

- Use the built-in len() function to find the number of characters in a string.

- Example: len(course) returns 18 if course = "Python Programming".
```python
# 17_strings.py
course = "Python programming"
print(len(course))
```

### Functions in Python

- A function is a reusable block of code that performs a task.

- Functions are called using parentheses: function_name(arguments).

- Some functions require arguments (inputs), like len(course).

### Accessing Characters (Indexing)

- Strings are zero-indexed, meaning the first character has index 0.

- Use square brackets [] to access specific characters: course[0] returns 'P'.
```python 
# 17_strings.py
course = "Python programming"
print(course[0])
```
- Negative indexing starts from the end: course[-1] returns 'g'.
```python
# 17_strings.py
course = "Python programming"
print(course[-1])
```
### Slicing Strings

- string[start:end] returns characters from start to end.
```python 
# 17_strings.py

course = "Python programming"
print(course[0:3])
```

- Omitting start starts from the beginning: course[:3] → 'Pyt'.
```python
# 17_strings.py
course = "Python programming"
print(course[:3])
```

- Omitting end slices to the end: course[0:]
```python
# 17_strings.py
course = "Python programming"
print(course[0:])
```

- course[:] returns a copy of the original string.
```python
# 17_strings.py
course = "Python programming"
print(course[:])
```

### Key Reminders

- Use len() for string length.

- Use [] for indexing characters.

- Use [start:end] for slicing.