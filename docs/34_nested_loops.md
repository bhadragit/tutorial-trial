# Chapter 34 - Nested loops
time duration: 1:30:42 - 1:33:26  
Here one loop is put inside another loop.

```python
# 34_nested_loops.py
for x in range(5):
    for y in range(3):
        print(f"({x}, {y})")
```

Output will be:
(0, 0)
(0, 1)
(0, 2)
(1, 0)
(1, 1)
...

Here you can see two loops, first one is outer loop and second one is inner loop.  
In the first iteration x=0 and y=0.  
In the second iteration x=0 and y=1.  
In the third iteration x=0 and y=2.  
Now again going back to outerloop this repeats x=1 and y=0, x=1 and y=1. 