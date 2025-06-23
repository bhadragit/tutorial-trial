# Chapter 42 - Keyword Arguments
Time duration: 1:53:59 - 1:55:59  
Take another function:

```python
# 42_keyword_arguments.py
def increment(number, by):
    return number + by

result = increment(2, 1)
print(result)
```

Here we don't need this long program. So it can be shortened like this:

```python
# 42_keyword_arguments.py
def increment(number, by):
    return number + by

print(increment(2, 1))
```

Now we can make this code more readable. For that you can use keyword arguments:

```python
# 42_keyword_arguments.py
print(increment(2, by=1))
```

If you're calling a function with multiple arguments, keyword arguments can be used to make it readable. 