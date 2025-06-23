# Chapter 23 - Type conversion
time duration: 58:59 - 1:04:03  
Here you are studying another useful built-in function. The input function is used to get input from the user.

```python
# 23_type_conversion.py
x = input("x: ")
y = x + 1
```

Don't run this code in the code runner extension because it will, by default, run your program in the output window, which is read-only.

So, open your terminal, type "python", and enter a value like 1.
You will get a "TypeError".

When you run "y = x + 1", the expression will look like "1" + 1.

Since these are two very different types, they cannot be concatenated.

Therefore, it has to be converted. So:

```python
# 23_type_conversion.py
# int(x)
# float(x)
# bool(x)
# str(x)
# these all can be used.
```

Let's type:

```python
# 23_type_conversion.py
x = input("x: ")
print(type(x))
# y = 2 + 1
```

"type" is another built-in function used to pass an object or an argument, and it returns its type.

```python
# 23_type_conversion.py
x = input("x: ")
y = int(x) + 1
print(f"x: {x}, y: {y}")
```

Anything of these used
-  0
-  ""
- None
- in boolean context are considered false.
- Anything other than this is true.

```python
# 23_type_conversion.py
bool(0)      # False
bool(1)      # True
bool(-1)     # True
bool(5)      # True
bool("a")    # True
bool("False") # True
``` 