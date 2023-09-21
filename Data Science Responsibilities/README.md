## Python Syllabus
### 1. Introduction to Python
### 2. Variables in Python
```python
x = 10
name = "Alice"
```
### 3. Data Types in Python
- **Numeric Types**
  - Integers (int)
  - Floating-Point Numbers (float)
  - Complex Numbers (complex)
```python
integer = 5              # Integer
floating_point = 3.14    # Float
complex_number = 2 + 3j  # Complex
```
- **Sequence Types**
  - Strings (str)
  - Lists (list)
  - Tuples (tuple)
  - Range (range)
```python
text = "Hello, World!"   # String
my_list = [1, 2, 3]      # List
my_tuple = (1, 2, 3)     # Tuple
my_range = range(5)      # Range
```
- **Mapping Type**
  - Dictionaries (dict)
```python
my_dict = {"name": "Alice", "age": 30}  # Dictionary
```
- **Set Types**
   - Sets (set)
   - Frozen Sets (frozenset)
```python
my_set = {1, 2, 3}      	     # Set
my_frozenset = frozenset({4, 5, 6})  # FrozenSet
```
- **Boolean Type (bool)**
```python
is_true = True            # Boolean (True)
is_false = False          # Boolean (False)
```
- **Binary Type**
```python
my_bytes = b'Hello'                                 # Bytes
my_bytearray = bytearray([72, 101, 108, 108, 111])  # Bytearray
my_memoryview = memoryview(b'Hello')                # Memoryview
```
- **None Type (NoneType)**
```python
my_none = None  # NoneType
```
### User Input & Type Casting in Python
```python
user_input = input("Enter a number: ")
num = int(user_input)  # Casting user input to an integer
```
### 4. Python Operators
- **Arithmetic Operators in Python**
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
  - Floor Division (//)
  - Modulus (%)
  - Exponentiation (**)
```python
x = 10
y = 5

addition = x + y          # Addition
subtraction = x - y       # Subtraction
multiplication = x * y    # Multiplication
division = x / y          # Division
floor_division = x // y   # Floor Division
exponentiation = x ** y   # Exponentiation
modulus = x % y           # Modulus
```
- **Assignment Operators in Python**
  - Assignment (=)
  - Addition Assignment (+=)
  - Subtraction Assignment (-=)
  - Multiplication Assignment (*=)
  - Division Assignment (/=)
  - Modulus Assignment (%=)
  - Exponentiation Assignment (**=)
  - Floor Division Assignment (//=)
```python
x = 10
x += 5   # Equivalent to x = x + 5
x -= 3   # Equivalent to x = x - 3
x *= 2   # Equivalent to x = x * 2
x /= 4   # Equivalent to x = x / 4
x //= 3  # Equivalent to x = x // 3
x **= 2  # Equivalent to x = x ** 2
x %= 7   # Equivalent to x = x % 7
```
- **Comparison Operators in Python**
  - Equal to (==)
  - Not equal to (!=)
  - Greater than (>)
  - Less than (<)
  - Greater than or equal to (>=)
  - Less than or equal to (<=)
```python
x = 10
y = 5
is_equal = x == y      # Equal to
not_equal = x != y     # Not equal to
greater_than = x > y   # Greater than
less_than = x < y      # Less than
greater_equal = x >= y # Greater than or equal to
less_equal = x <= y    # Less than or equal to
```
- **Logical Operators in Python**
  - Logical AND (and)
  - Logical OR (or)
  - Logical NOT (not)
```python
x = True
y = False

logical_and = x and y  # Logical AND
logical_or = x or y    # Logical OR
logical_not = not x    # Logical NOT
```
- **Membership Operators in Python**
  - Membership Test (in)
  - Negated Membership Test (not in)
```python
fruits = ["apple", "banana", "cherry"]

is_in_list = "banana" in fruits          # Check if an item is in a list
is_not_in_list = "orange" not in fruits  # Check if an item is not in a list
```
- **Identity Operators in Python**
  - Identity Test (is)
  - Negated Identity Test (is not)
```python
x = ["apple", "banana"]
y = ["apple", "banana"]
z = x

is_same_object = x is z          # Check if two variables reference the same object
is_not_same_object = x is not y  # Check if two variables reference different objects
```
- **Bitwise Operators in Python**
  - Bitwise AND (&)
  - Bitwise OR (|)
  - Bitwise XOR (^)
  - Bitwise NOT (~)
  - Left Shift (<<)
  - Right Shift (>>)
```python
x = 10
y = 5

bitwise_and = x & y    # Bitwise AND
bitwise_or = x | y     # Bitwise OR
bitwise_xor = x ^ y    # Bitwise XOR
bitwise_not_x = ~x     # Bitwise NOT for x
left_shift = x << 2    # Left shift x by 2 bits
right_shift = x >> 1   # Right shift x by 1 bit
```
### 5. Conditional Statements:
  - If, If Else & If Elif Else Conditional Statements in Python
```python
    x = 3
    if x > 5:
        print("x is greater than 5")
    elif x == 5:
        print("x is equal to 5")
    else:
        print("x is less than 5")
```
### 6. Loops in Python:
  - For Loop with Range () in Python
  - While Loop in Python
```python
# For Loop with Range in Python
for i in range(1, 5):  # Loop from 1 to 4
    print(i)

# While Loop in Python
count = 0
while count < 5:  # Loop until count is less than 5
    print("Count:", count)
    count += 1
```
### 7. String Manipulation
  - **String Concatenation in Python**
```python
      first_name = "John"
      last_name = "Doe"
      full_name = first_name + " " + last_name
```
  - **String Indexing & String Slicing in Python**
```python
text = "Hello, World!"
print(text[0])       # Access the first character 'H'
print(text[7:12])    # Slice and print 'World'
```
  - **String Iteration in Python**
```python
text = "Python"
for char in text:
    print(char)  # Iterate and print each character in the string
```
  - **Lower, Upper, Title & Capitalize String Functions in Python**
```python
text = "python programming"
print(text.lower())      # Convert to lowercase
print(text.upper())      # Convert to uppercase
print(text.title())      # Convert to title case
print(text.capitalize()) # Capitalize the first character
```
  - **Find, Index, Isalpha, Isdigit & Isalnum String Functions in Python**
```python
text = "Hello, 123"
print(text.find("l"))        # Find the first occurrence of 'l'
print(text.index("123"))     # Get the index of '123'
print(text.isalpha())        # Check if all characters are alphabetic
print(text.isdigit())        # Check if all characters are digits
print(text.isalnum())        # Check if all characters are alphanumeric
```
  - **Ord() and Chr() Functions in Python**
```python
char = 'A'
print(ord(char))    # Get the Unicode code point of 'A'
unicode_code = 97
print(chr(unicode_code))  # Get the character for Unicode code 97
```
  - **String Format () Method in Python**
```python
name = "Alice"
age = 30
print("My name is {} and I am {} years old.".format(name, age))
# Using f-strings (Python 3.6+)
print(f"My name is {name} and I am {age} years old.")
```
