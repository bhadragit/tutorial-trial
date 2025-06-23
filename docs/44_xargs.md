# Chapter 44 - Xargs
time duration: 1:57:34 - end
```python
# 44_xargs.py
def multiply(x, y):
    return x * y

multiply(2, 3)
```

Here only two parameters can be used.

For if you want to pass one or more or two arguments:

```python
# 44_xargs.py
def multiply(*numbers):
    total = 1
    for number in numbers:
        total *= number
    return total

print(multiply(2, 3, 4, 5))
``` 