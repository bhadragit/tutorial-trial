# Chapter 35 - Iterables
time duration: 1:33:26 - 1:33:26  
type() -> type of an object can be determined.

type(range()) -> range function returns the type of object in range.

```python
# 35_iterables.py
print(type(5))
print(type(range(5)))
```

A range object is iterable, which means you can use it in a for loop.  
Example: "for x in range(5):"

Ranges are not the only iterable objects in python, strings are also iterable.
Example:
```python
# 35_iterables.py
for x in "python":
    print(x)
```

Lists are also iterable.
Example:
```python
# 35_iterables.py
for x in [1, 2, 3, 4]:
    print(x)
``` 