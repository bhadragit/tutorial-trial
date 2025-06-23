# Chapter 32 - For loops
time duration: 1:24:18 - 1:27:56  
At times you may need to repeat a task a number of times for that 'for' loop can be used.

```python
# 32_for_loops.py
print("Sending a message")
```

If you want to repeat this code multiple times use for loop.

```python
# 32_for_loops.py
for number in range(3):
    print("Attempt")
```

To know more about number, you can change the above code:

```python
# 32_for_loops.py
for number in range(3):
    print("Attempt", number)
```

Also try

```python
# 32_for_loops.py
for number in range(3):
    print("Attempt", number + 1, (number + 1) * ".")
```

Output will be
Attempt 1 .
Attempt 2 ..
Attempt 3 ...

Range function generates starting from 0 till the given number. To avoid that we can change the above code like this:

```python
# 32_for_loops.py
for number in range(1, 4):
    print("Attempt", number, number * ".")
```

Output will be same.

```python
# 32_for_loops.py
for number in range(1, 10, 2):
    print("Attempt", number, number * ".")
```

Output will be:
Attempt 1 .
Attempt 3 ...
Attempt 5 .....
Attempt 7 .......
Attempt 9 .........

"range(1, 10, 2)" here 1 is start, (1, 10) is range and 2 is the difference. 