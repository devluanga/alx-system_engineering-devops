0x04. Loops, conditions and parsing

1. Loops:
Loops are used to repeatedly execute a block of code until a specific condition is met. In Python, there are two types of loops: `for` loop and `while` loop.

- `for` loop: It iterates over a sequence (such as a list, tuple, string, or range) or any iterable object. Here's an example:

```python
for item in iterable:
    # code to be executed
```

- `while` loop: It repeatedly executes a block of code as long as the given condition is true. Here's an example:

```python
while condition:
    # code to be executed
    # condition update
```

2. Conditions:
Conditions are used to perform different actions based on specific criteria. In Python, you can use conditional statements like `if`, `elif` (short for "else if"), and `else`.

```python
if condition:
    # code to be executed if the condition is true
elif another_condition:
    # code to be executed if the previous condition is false and this condition is true
else:
    # code to be executed if none of the above conditions are true
```

3. Parsing:
Parsing involves extracting specific information from a given input, such as a string or a file. Python provides various libraries and modules to facilitate parsing, such as `re` for regular expressions and `json` for working with JSON data.

For example, to parse a JSON string, you can use the `json` module as follows:

```python
import json

json_string = '{"name": "John", "age": 30}'
data = json.loads(json_string)

name = data['name']
age = data['age']
```

This code parses the JSON string and retrieves the values of the "name" and "age" keys.

These are just the basics of loops, conditions, and parsing in Python. Let me know if you have any specific questions or if there's anything else I can assist you with!
