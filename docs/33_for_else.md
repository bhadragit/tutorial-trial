# Chapter 33 For else
time duration: 1:27:56 - 1:30:42  
```python
# 33_for_else.py
successful = True
for number in range(3):
    print("Attempt")
    if successful:
        print("Successful")
        break
else:
    print("Attempted 3 times and failed")
```

Change "successful" to "false" and you can see the output varies.

For else is the combination of for loop with else clause. 