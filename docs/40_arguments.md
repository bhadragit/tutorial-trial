# Chapter 40 - Arguments
Time duration - 1:47:37 - 1:49:57  
In the previous chapter, do you know what is the difference between greet function and print function? The difference is that print function takes an input whereas greet function doesn't take any.

Here you are going to learn how to pass inputs like first name and last name to this function.

```python
# 40_arguments.py
def greet(first_name, last_name):
```

The list parameters between parentheses.

When calling this function you should put two values, and these are referred to as arguments. Argument is the most common word used by developers. Many are confused between parameter and argument. Parameter is the input that you define for your function and argument is the actual value for a given parameter.

```python
# 40_arguments.py
def greet(first_name, last_name):
    print(f"Hi {first_name} {last_name}")
    print("Welcome aboard")

greet("Mosh", "Hamedani")
greet("John", "Smith")
```

Here greet function should take two parameters. If only one argument is given while running this function, then it will show error saying missing 1 required positional argument. 