# Chapter 36 - While loops
time duration: 1:36:34 - 1:41:33  
A while loop is used to repeat something as long as a given condition is true.

Example:
```python
# 36_while_loops.py
number = 100
while number > 0:
    print(number)
    number = number // 2
```

Here you are evaluating a condition and repeating tasks.

```python
# 36_while_loops.py
command = ""
while command != "quit":
    command = input(">")
    print("ECHO", command)
```

This code is to create a simple interactive program that keeps taking input from the user and repeating it until the user types "quit".

If you type "QUIT" instead of "quit", it will not work. As you learned before, python is case sensitive, so lowercase and uppercase have different numerical presentations.

If you want to run the program with "QUIT" also, change the code like this:

```python
# 36_while_loops.py
command = ""
while command != "quit" and command != "QUIT":
    command = input(">")
    print("ECHO", command)
```

OR

Use command.lower() 