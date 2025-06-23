# Chapter 29 - Short circuit evaluations
time duration: 1:19:07 - 1:21:13
```python
# 29_short_circuit_evaluations
high_income = False
good_credit = True
student = True

if high_income and good_credit and not student:
    print("eligible")
```

Result of the above if expression will always be false because one of the argument is false.

This is called short circuiting.

If "and" is changed to "or", then the expression becomes true.

In Python logical operators are short circuiting. 