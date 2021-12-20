---
title: Python string functions
description: some built-in functions of string datatype
author: gokulap
date: 2021-12-20
categories: [python]
tags: [python, string, functions]
---

# Python String Funtions

```python
# string concatenation

string1 = 'tamil'
string2 = 'ctf'

string = string1 + string2
print(string)

# converting string to uppercase

string.upper()
print(string)

# converting string to lowercase

string.lower()
print(string)

# capitalise and title the string

string.capitalize()
print(string)
string.title()
print(string)

# Find the index of letter 'c' in 'tamilctf'

index = string.find('c')
print(index)

# Replace a part of string with new string

string.replace('ctf', 'CTF')
print(string)

# Traversing a string with loop

for i in string:
   print(i)

# converting string into a list

list_of_chars = list(string)

for char in list_of_chars:
    print(char)
    
# convert list into string

list_to_string = ''.join(list_of_chars)
print(list_to_string)
```

*Hope you learnt about some functions*


