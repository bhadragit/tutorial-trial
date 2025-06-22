# Chapter 20 - String method
time duration: 48:09 - 54:03
In this chapter, you are going to study about a few essential functions available to work with strings. 
```python 
# 20_string_functions
course = "python programming"
print(len(course))
```
You learned about len function in previous chapters. This function is not only for string but also used generally.  
Few functions that are specific to strings are there in python. You can see the available functions below:

![syntax demo](/images/20_string_methods.png)

### Note:
Everything in python is an object and every object has functions (also called methods) that you can access through dot notation.  

Lets look at some functions: 
- This function is for making all letters uppercase.
```python
# 20_string_methods
course = " python programming "
print(course.upper())
```
- This function if for making all letters lowercase
```python
# 20_string_methods
course = " python programming "
print(course.lower())
```
- This function is to make the first letter capital
```python
# 20_string_methods
course = " python programming "
print(course.title())
```
- This function is to remove white spaces in the string
```python
# 20_string_methods
course = " python programming "
print(course.strip())
```
- This function is to remove white space from the left
```python
# 20_string_methods
course = " python programming "
print(course.lstrip())
```
- This function is to remove white space from the right
```python
# 20_string_methods
course = " python programming "
print(course.rstrip())
```
- This function is to find index 
```python
# 20_string_methods
course = " python programming "
print(course.find("pro"))
```
- This function is to replace letters.
```python
# 20_string_methods
course = " python programming "
print(course.replace("p","j"))
```
- This function is to check whether certain string is present in the given string
```python
# 20_string_methods
course = " python programming "
print("pro" in course)
print("swift" not in course)
```