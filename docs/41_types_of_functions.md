# Chapter 41 - Types of Functions
Time duration: 1:49:57 - 1:53:59  
There are two types of functions:

1) Functions that perform a task
2) Functions that calculate and return a value

**Examples:**

The round() function is an example of a second function:
```python
# 41_types_of_functions.py
round(2.8)
```

Functions that you create fall into both categories:

```python
# 41_types_of_functions.py
def greet(name):
    print(f"Hi {name}")
```

This program is not included in the first category.

It can be rewritten into the second category:
```python
# 41_types_of_functions.py
def get_greeting(name):
    return f"Hi {name}"

message = get_greeting("Mosh")
```

With the print message implementation we are limited to printing it in the terminal. Here we cannot reuse the greet function in other scenarios.

In the second implementation, it simply returns a value and we can do anything with that. Also we use it in built-in functions and open it for writing.

What if we put `greet("Mosh")` inside print function?

```python
# 41_types_of_functions.py
def greet(name):
    print(f"Hi {name}")

print(greet("Mosh"))
```

We get output as "Hi Mosh" followed by "None".

"None" is the return value of greet function.

In Python all functions by default return the None value. None is an object that represents the absence of a value.

Even though this function returns None, it is still classified as a function that carries out the task. 