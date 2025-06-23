# Chaper 30 - Chaining Comparison Operators
time duration: 1:21:13 - 1:22:35  
This is very powerful technique for writing clear code.

```python
# 30_chaining_comparison_operators.py
# age should be between 18 and 65
age = 22
if age >= 18 and age < 65:
    print("eligible")
```

We write this same rule in maths like this:  
18 <= age < 65

This expression can be written same in Python. Rewrite it the above code as:

```python
# 30_chaining_comparison_operators.py
age = 22
if 18 <= age < 65:
    print("eligible")
```

This is called chaining comparison operators. 