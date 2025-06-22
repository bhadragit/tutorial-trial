# Chapter 19 - Formatted strings
time duration: 46:01 - 48:09  

```python
# 19_formatted_strings1.py
first = "Mosh"
last = "Hamedani"
full = first + " " + last 
print(full)
```
Here first and last variable is concatenated. There is better and newer approach other than concatenation.i.e, formatted strings.

```python
# 19_formatted_strings2.py
first = "Mosh"
last = "Hamedani"
full = f"{first} {last}"
print(full)
```
We can call len here:

```python
# 19_formatted_strings2
full = f"{len(first)} {2+2}"
```
In formatted string you can put any valid expression.