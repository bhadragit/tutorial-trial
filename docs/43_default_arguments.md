# Chapter 43 - Default Arguments
Time duration: 1:55:59 - 1:57:34  
All parameters defined for a function are required by default.

This parameter below is given a default value:

```python
# 43_default_arguments.py
def increment(number, by=1):
    return number + by

print(increment(2))
```

In this case we have set a default argument. 