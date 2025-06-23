# Chapter 27 - Ternary Operator
time duration: 1:12:56 - 1:15:04  
The ternary operator is a conditional operator, that helps you for concisely expressing if-else statements in a single line of code

```python
# 27_ternary_operator.py
age = 22
if age >= 18:
    message = "Eligible"
else:
    message = "Not eligible"
print(message)
```

- This can also be written in another way:

```python
# 27_ternary_operator.py
message = "Eligible" if age >= 18 else "Not eligible"
print(message)
```

So, what we have here is called a Ternary operator. 