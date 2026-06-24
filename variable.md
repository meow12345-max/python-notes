#variable:
##assign values:-
- spam = 40
- spam = spam+2
- spam 40
- so everytime you assign new value old value is forgotten or replace
## Variable Names

###Rules:

- Cannot contain spaces
- Cannot begin with a number
- Cannot be a Python keyword ('if','for','while' etc.)
- Can only contain letters, numbers, and underscores ('_')
- Hyphens ('-') are not allowed
- Special characters such as '$', ''@', '!' are not allowed
- Variable names are case-sensitive

###Examples:

'''python
name = "John"
user_name = "John"
age2 = 19
'''

---

## Comments

Python ignores comments.

```python
# This is a comment
```

Programmers sometimes put a `#` in front of code to temporarily disable it while testing.

This is called **commenting out code**.

```python
# print("Hello")
```

---

## String Concatenation

Concatenation means joining strings together.

```python
name = input("Enter your name: ")
print("Hello, " + name)
```

You can only concatenate strings with strings.
