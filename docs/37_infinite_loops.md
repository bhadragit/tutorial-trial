# Chapter 37 - Infinite loops
time duration: 1:41:33 - 1:43:10  
An infinite loop is a loop that runs forever. If the code you studied in the last chapter is changed in the given way:

```python
# 37_infinite_loops.py
command = ""
while True:
    command = input(">")
    print("ECHO", command)
```

Here "True" is always true, therefore this while loop will run forever.

So to jump out from this loop you need a "break" statement. For an infinite loop, there is no need to define the command.

Therefore:

```python
# 37_infinite_loops.py
while True:
    command = input(">")
    print("ECHO", command)
    if command.lower() == "quit":
        break
```

You should be aware of infinite loops because they run forever and you should always know a way to jump out of it. If the program runs forever, it can cause issues with consuming memory and your program may run out of memory. 