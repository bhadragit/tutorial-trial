# Chapter 18 - Escape Sequences
time duration: 43:20 - 46:01  
In Python, text is written using either single quotes (' ') or double quotes (" ").

If you need to include a quote character inside your string (like a double quote in a double-quoted string), it causes a problem because Python thinks the string ends there.

✅ Example of an error: "Python "Programming" ← Python gets confused here.
```python
# 18_escape_sequences
course = "Python "Programming"
print(course)
```

✅ How to Fix It
Use the other type of quote:

'Python "Programming' → No conflict, so this works.
```python
# 18_escape_sequences
course = 'Python "programming"
print(course)
```
- Use a backslash ( \ ) to escape the quote:

"Python \"Programming" → The backslash tells Python to treat the next character as part of the string.
```python
# 18_escape_sequences
course = "Python \"Programming"
print(course)
```

- Escape Characters (Escape Sequences)
The backslash ( \ ) is an escape character, used to give special meaning to the character that follows.

### Common escape sequences:

- \ " → Inserts a double quote inside a double-quoted string.
👉 Example: "He said, \"Hello\"" → Output: He said, "Hello"

- \ ' → Inserts a single quote inside a single-quoted string.
👉 Example: 'It\'s okay' → Output: It's okay

- \ \ → Inserts one backslash (\).
👉 Example: "Path: C:\\Program Files" → Output: Path: C:\Program Files

- \n → Creates a new line in the string.