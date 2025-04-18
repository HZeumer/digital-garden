An example for a codeblock for Python:

Default Codeblock

```py
# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result: = add_two_numbers(5, 3)
print('The sum is:', result)
```

Codeblock mit Titel

```py title="add_numbers.py" 
# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5, 3)
print('The sum is:', result)
```

Codeblock mit Titel und Zeilennummern

```py title="add_numbers.py" linenums="1"
# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5, 3)
print('The sum is:', result)
```

Codeblock bei dem Zeilen hervorgehoben werden

```py title="add_numbers.py" linenums="1" hl_lines="2-3"
# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5, 3)
print('The sum is:', result)
```