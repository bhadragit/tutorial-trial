# Chapter 28 - Logical Operators
time duration: 1:15:04 - 1:19:07  
There are three logical operators in Python.

These operators are used to model more complex conditions.

- and
- or
- not

```python
# 28_logical_operators.py
high_income = False
good_credit = True

if high_income and good_credit:
    print("Eligible")
else:
    print("Not eligible")
```

Here "or" can be given instead of "and".

Also "not" is used:

```python
# 28_logical_operators
high_income = False
good_credit = True
student = False

if not student:
    print("Eligible")
else:
    print("Not eligible")
```

We want neither high_income or good_credit should be true to be true so use parenthesis. Code given:

```python
# 28_logical_operators
if (high_income or good_credit) and not student:
    print("Eligible")
else:
    print("Not eligible")
``` 