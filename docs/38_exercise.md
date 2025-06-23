# Chapter 38 - Exercise
time duration: 1:43:10 - 1:45:13  
**Question:**
Write a program to display even numbers from 1 to 10 and after that print this message: "We have 4 even numbers."

**Answer:**
```python
# 38_exercise.py
count = 0
for number in range(1, 10):
    if number % 2 == 0:
        print(number)
        count += 1
print(f"We have {count} even numbers")
``` 