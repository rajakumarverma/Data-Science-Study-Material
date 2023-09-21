## Python
### 1. Introduction to Python
Python is a versatile and popular programming language known for its simplicity, readability, and a wide range of applications. It was created by Guido van Rossum and first released in 1991. 
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
### 4. User Input & Type Casting in Python
```python
user_input = input("Enter a number: ")
num = int(user_input)  # Casting user input to an integer
```
### 5. Python Operators
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
### 6. Conditional Statements:
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
### 7. Loops in Python:
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
### 8. String Manipulation
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
### 9. List Manipulation
  - **List Iteration in Python**
```python
my_list = [1, 2, 3, 4, 5]
for item in my_list:
    print(item)
```
  - **List Function - (Pop, Remove & Clear) List Method**
```python
my_list = [1, 2, 3, 4, 5]
popped_element = my_list.pop(2)  # Remove and return element at index 2
my_list.remove(4)  # Remove the first occurrence of 4
my_list.clear()    # Clear the list, making it empty
```
  - **Python List Comprehension - Elegant way to Create Lists**
```python
my_list = [x for x in range(1, 6)]  # Creates a list of numbers from 1 to 5
```
  - **Count, Max, Min, Sort, Reverse & Index List Function**
```python
my_list = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3]
count_of_1 = my_list.count(1)  # Count occurrences of 1
max_value = max(my_list)      # Find the maximum value
min_value = min(my_list)      # Find the minimum value
my_list.sort()                # Sort the list in ascending order
my_list.reverse()             # Reverse the list
index_of_5 = my_list.index(5) # Find the index of the first occurrence of 5
```
  - **Zip Function - Iterate Over 2+ Lists at the Same Time**
```python
names = ["Alice", "Bob", "Charlie"]
scores = [85, 92, 78]
for name, score in zip(names, scores):
    print(f"{name}: {score}")
```
  - **Python Program to Convert String to a List**
```python
my_string = "Hello, World!"
my_list = list(my_string)  # Convert the string to a list of characters
```
  - **Implement a Stack and Queue Using a List Data Type**
```python
# Stack implementation
my_stack = []
my_stack.append(1)  # Push an element onto the stack
popped_element = my_stack.pop()  # Pop an element from the stack

# Queue implementation
from collections import deque
my_queue = deque()
my_queue.append(1)  # Enqueue an element
dequeued_element = my_queue.popleft()  # Dequeue an element
```
### 10. Dictionary Manipulation
  - **Creating a Dictionary:**
```python
my_dict = {"name": "Alice", "age": 30, "city": "New York"}
```

  - **Accessing Dictionary Elements (Key-Value Pairs):**
```python
name = my_dict["name"]  # Accessing the value associated with the key "name"
```

  - **Modifying Dictionary Elements:**
```python
my_dict["age"] = 31  # Modifying the value associated with the key "age"
```

  - **Adding and Removing Elements from Dictionaries:**
```python
my_dict["gender"] = "Female"  # Adding a new key-value pair
del my_dict["city"]           # Removing a key-value pair
```

  - **Dictionary Iteration (Keys, Values, Items):**
```python
for key in my_dict:
    print(key, my_dict[key])

for value in my_dict.values():
    print(value)

for key, value in my_dict.items():
    print(key, value)
```

  - **Checking if a Key Exists in a Dictionary:**
```python
if "name" in my_dict:
    print("Key 'name' exists in the dictionary")
```

  - **Dictionary Comprehension:**
```python
squared_values = {key: value ** 2 for key, value in my_dict.items()}
```

  - **Nested Dictionaries:**
```python
nested_dict = {"person": {"name": "Bob", "age": 25}}
```

  - **Dictionary Methods (e.g., keys(), values(), items(), get(), pop(), popitem(), clear(), update()):**
```python
keys = my_dict.keys()
values = my_dict.values()
items = my_dict.items()
value = my_dict.get("age")
my_dict.pop("city")
my_dict.popitem()
my_dict.clear()
my_dict.update({"country": "USA"})
```

  - **Dictionary Length:**
```python
length = len(my_dict)
```

  - **Dictionary Aliasing:**
```python
alias_dict = my_dict  # Creating an alias to the original dictionary
```

  - **Merging Dictionaries:**
```python
dict1 = {"a": 1, "b": 2}
dict2 = {"b": 3, "c": 4}
merged_dict = {**dict1, **dict2}  # Merging two dictionaries
```

  - **Sorting Dictionaries (by keys or values):**
```python
sorted_dict = dict(sorted(my_dict.items()))  # Sorting by keys
sorted_dict = dict(sorted(my_dict.items(), key=lambda item: item[1]))  # Sorting by values
```

  - **Copying Dictionaries (shallow and deep copies):**
```python
import copy

shallow_copy = copy.copy(my_dict)  # Shallow copy
deep_copy = copy.deepcopy(my_dict)  # Deep copy
```

  - **Dictionary with Default Values (using defaultdict):**
```python
from collections import defaultdict

default_dict = defaultdict(int)  # Default value is 0 for missing keys
```

  - **Dictionary with Ordered Keys (using OrderedDict):**
```python
from collections import OrderedDict

ordered_dict = OrderedDict()  # Maintains the order of keys
```

  - **Dictionary as a Switch Case (using get()):**
```python
def switch_case(option):
    switch_dict = {
        1: "Option 1",
        2: "Option 2",
        3: "Option 3"
    }
    return switch_dict.get(option, "Invalid Option")
```
### 11. Tuples Manipulation
  - **Creating a Tuple:**
```python
my_tuple = (1, 2, 3, 4, 5)
```

  - **Accessing Tuple Elements (Indexing):**
```python
element = my_tuple[2]  # Accessing the element at index 2 (zero-based indexing)
```

  - **Modifying Tuples (Immutability):**
```python
# Tuples are immutable, so you cannot modify their elements directly.
# You can create a new tuple with the desired changes.
new_tuple = my_tuple + (6, 7)
```

  - **Tuple Packing and Unpacking:**
```python
# Tuple packing
my_packed_tuple = 1, "hello", 3.14

# Tuple unpacking
a, b, c = my_packed_tuple
```

  - **Tuple Iteration:**
```python
for item in my_tuple:
    print(item)
```

  - **Tuple Concatenation and Repetition:**
```python
concatenated_tuple = my_tuple + (6, 7)
repeated_tuple = my_tuple * 3
```

  - **Tuple Slicing:**
```python
sliced_tuple = my_tuple[1:4]  # Slicing from index 1 to 3 (exclusive)
```

  - **Counting Elements in a Tuple:**
```python
count = my_tuple.count(3)  # Count occurrences of the value 3
```

  - **Finding the Index of an Element in a Tuple:**
```python
index = my_tuple.index(4)  # Find the index of the first occurrence of 4
```

  - **Checking if an Element Exists in a Tuple:**
```python
exists = 5 in my_tuple  # Check if 5 exists in the tuple
```

  - **Tuple Methods (e.g., index() and count()):**
```python
index = my_tuple.index(4)  # Find the index of the first occurrence of 4
count = my_tuple.count(3)  # Count occurrences of the value 3
```

  - **Using Tuples for Multiple Return Values:**
```python
def get_name_age():
    return "Alice", 30

name, age = get_name_age()
```

  - **Named Tuples:**
```python
from collections import namedtuple

Person = namedtuple("Person", ["name", "age"])
person = Person(name="Alice", age=30)
```

  - **Tuple Length:**
```python
length = len(my_tuple)
```

  - **Tuple Aliasing:**
```python
alias_tuple = my_tuple  # Creating an alias to the original tuple
```

  - **Converting Lists to Tuples and Vice Versa:**
```python
my_list = [1, 2, 3]
my_tuple = tuple(my_list)  # Convert a list to a tuple
my_list = list(my_tuple)    # Convert a tuple to a list
```

  - **Sorting Tuples:**
```python
sorted_tuple = tuple(sorted(my_tuple))  # Sorting a tuple
```

  - **Immutable Nature of Tuples:**
```python
my_tuple[0] = 10  # This will result in an error because tuples are immutable.
```

  - **Tuple Membership Testing:**
```python
is_present = 5 in my_tuple  # Check if 5 is present in the tuple
```
### 12. Set Manipulation
  - **Adding Elements to a Set:**
```python
my_set.add(6)  # Adding a single element
my_set.update([7, 8, 9])  # Adding multiple elements using update()
```

  - **Removing Elements from a Set:**
```python
my_set.remove(3)  # Removing an element (raises an error if not found)
my_set.discard(4)  # Removing an element (no error if not found)
my_set.pop()  # Removing and returning an arbitrary element
```

  - **Set Operations (Union, Intersection, Difference, Symmetric Difference):**
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}
union_set = set1 | set2  # Union of two sets
intersection_set = set1 & set2  # Intersection of two sets
difference_set = set1 - set2  # Set difference
symmetric_difference_set = set1 ^ set2  # Symmetric difference
```

  - **Set Membership Testing:**
```python
is_present = 5 in my_set  # Check if 5 is present in the set
```

  - **Set Iteration:**
```python
for element in my_set:
    print(element)
```

  - **Checking if a Set is a Subset or Superset of Another Set:**
```python
subset_check = {1, 2}.issubset(my_set)  # Check if {1, 2} is a subset of my_set
superset_check = my_set.issuperset({1, 2})  # Check if my_set is a superset of {1, 2}
```

  - **Set Comprehension:**
```python
squared_set = {x**2 for x in my_set}
```

  - **Frozen Sets:**
```python
frozen_set = frozenset([1, 2, 3, 4, 5])  # Creating an immutable set
```

  - **Set Methods (e.g., add(), remove(), discard(), pop(), clear()):**
```python
my_set.add(6)
my_set.remove(3)
my_set.discard(4)
my_set.pop()
my_set.clear()
```

  - **Set Length:**
```python
length = len(my_set)
```

  - **Converting Lists to Sets and Vice Versa:**
```python
my_list = [1, 2, 3, 4, 5]
my_set = set(my_list)  # Convert a list to a set
my_list = list(my_set)  # Convert a set to a list
```

  - **Set Aliasing:**
```python
alias_set = my_set  # Creating an alias to the original set
```

  - **Immutable Nature of Sets:**
```python
my_set.add(6)  # You can modify a set, but you cannot modify its elements.
```

  - **Set Equality and Comparison:**
```python
set1 = {1, 2, 3}
set2 = {3, 2, 1}
are_equal = set1 == set2  # Check if two sets are equal (order doesn't matter)
```

  - **Set Disjoint Sets:**
```python
set1 = {1, 2, 3}
set2 = {4, 5, 6}
are_disjoint = set1.isdisjoint(set2)  # Check if two sets are disjoint (no common elements)
```
### 13. Fuctions in Python
  - **Built-in Functions**:
These are functions that are built into the Python language and are available for use without the need to import any additional modules. Examples include print(), len(), max(), min(), and range().
   ```python
   # Example of the `print()` function
   print("Hello, World!")

   # Example of the `len()` function
   length = len([1, 2, 3, 4, 5])
   print(length)  # Output: 5
   ```

  - **User-Defined Functions**: These functions are created by the user to perform specific tasks. User-defined functions help encapsulate and reuse code. They are defined using the def keyword.
   ```python
   # Example of a user-defined function
   def add_numbers(a, b):
       result = a + b
       return result

   # Calling the user-defined function
   sum_result = add_numbers(10, 5)
   print(sum_result)  # Output: 15
   ```

  - **Lambda Functions (Anonymous Functions)**: Lambda functions are small, anonymous functions defined using the lambda keyword. They are often used for short, simple operations and can be passed as arguments to higher-order functions.
   ```python
   # Example of a lambda function
   add = lambda x, y: x + y
   result = add(3, 4)
   print(result)  # Output: 7
   ```

  - **Generator Functions**: Generator functions use the yield keyword to create iterators that produce a sequence of values lazily, one at a time. They are memory-efficient for handling large datasets.
   ```python
   # Example of a generator function
   def countdown(n):
       while n > 0:
           yield n
           n -= 1

   # Using the generator
   for num in countdown(5):
       print(num)
   # Output: 5 4 3 2 1
   ```

  - **Class Constructors (Methods)**: Functions with special names like __init__ serve as constructors for classes. They are called when creating instances of a class and initialize the object's attributes.
   ```python
   # Example of a class with a constructor method
   class Person:
       def __init__(self, name, age):
           self.name = name
           self.age = age

   # Creating an instance of the class
   person1 = Person("Alice", 30)
   ```

  - **Decorator Functions**: Decorator functions are used to modify the behavior of other functions or methods. They are applied using the @decorator syntax.
   ```python
   # Example of a decorator function
   def my_decorator(func):
       def wrapper():
           print("Something is happening before the function is called.")
           func()
           print("Something is happening after the function is called.")
       return wrapper

   @my_decorator
   def say_hello():
       print("Hello!")

   say_hello()
   ```

  - **Library Functions**: Functions provided by external libraries and modules that extend Python's capabilities. Examples include functions from the math, numpy, and pandas libraries.
   ```python
   # Example using a function from the `math` library
   import math

   square_root = math.sqrt(25)
   print(square_root)  # Output: 5.0
   ```

  - **Custom Modules and Packages**: Functions defined in user-created modules and packages to organize and modularize code in larger projects.
   Suppose you have a module named `my_module.py` with the following function:

   ```python
   # my_module.py
   def greet(name):
       return f"Hello, {name}!"

   # In another Python script, you can use this module and function
   import my_module

   greeting = my_module.greet("John")
   print(greeting)  # Output: "Hello, John!"
   ```
### 14. Modules in Python

Modules in Python are files that contain Python code, including functions, variables, and classes, which can be reused in other Python scripts. You can import modules using the `import` statement. Here's how it works:

```python
import module_name  # Imports the entire module
```

Example:

```python
import math
print(math.sqrt(25))  # Output: 5.0
```

  - **Math Module in Python**

The `math` module provides mathematical functions and constants. Here are some common math functions:

```python
import math

# Example: Calculating the factorial of a number
factorial = math.factorial(5)  # 5! = 120
```

  - **Random Module in Python**

The `random` module is used for generating random numbers and making random selections. Here's an example of generating a random number:

```python
import random

# Generate a random integer between 1 and 10
random_number = random.randint(1, 10)
```

  - **Datetime Module in Python**

The `datetime` module provides classes for working with dates and times. Here's an example of getting the current date and time:

```python
import datetime

current_time = datetime.datetime.now()
print(current_time)
```

  - **Python - Random Number Guessing Game (Using Random Module)**

Here's a simple example of a random number guessing game using the `random` module:

```python
import random

# Generate a random number between 1 and 100
secret_number = random.randint(1, 100)

guess = int(input("Guess the secret number (between 1 and 100): "))

if guess == secret_number:
    print("Congratulations! You guessed the secret number.")
else:
    print(f"Sorry, the secret number was {secret_number}. Try again.")
```

  - **Python - Rock, Paper, Scissors Game (Using Random Module)**

Here's an example of a rock, paper, scissors game using the `random` module:

```python
import random

choices = ["rock", "paper", "scissors"]

user_choice = input("Choose rock, paper, or scissors: ").lower()
computer_choice = random.choice(choices)

if user_choice in choices:
    if user_choice == computer_choice:
        print(f"It's a tie! Computer also chose {computer_choice}.")
    elif (
        (user_choice == "rock" and computer_choice == "scissors")
        or (user_choice == "paper" and computer_choice == "rock")
        or (user_choice == "scissors" and computer_choice == "paper")
    ):
        print(f"You win! Computer chose {computer_choice}.")
    else:
        print(f"You lose! Computer chose {computer_choice}.")
else:
    print("Invalid choice. Please choose rock, paper, or scissors.")
```

  - **Pickle Module**

The `pickle` module in Python is used for serializing and deserializing Python objects. It allows you to save and load Python objects to and from files. Here's a basic example:

```python
import pickle

# Serialize (save) an object to a file
data = [1, 2, 3, 4, 5]
with open("data.pkl", "wb") as file:
    pickle.dump(data, file)

# Deserialize (load) an object from a file
with open("data.pkl", "rb") as file:
    loaded_data = pickle.load(file)
```
### 15. JSON in Python

JSON (JavaScript Object Notation) is a lightweight data interchange format. In Python, you can work with JSON data using the `json` module.

  - **Convert JSON Data to Python Object**

```python
import json

# JSON string
json_str = '{"name": "Alice", "age": 30}'

# Convert JSON to a Python dictionary
data = json.loads(json_str)
```

  - **Reading and Writing JSON File in Python**

```python
import json

# Write data to a JSON file
data = {"name": "Bob", "age": 25}
with open("data.json", "w") as file:
    json.dump(data, file)

# Read data from a JSON file
with open("data.json", "r") as file:
    loaded_data = json.load(file)
```
### 16. Object-Oriented Programming (OOP) in Python
  - **Objects are like Things:** Think of objects as things or stuff. Just like you have objects in the real world (like a car, a book, or a person), you can create objects in Python.

  - **Classes are like Blueprints:** Imagine a class as a blueprint or a plan for creating objects. It defines what an object will be like and what it can do. For example, a class for a "Car" can define how a car looks and what actions it can perform (like driving or honking).

  - **Attributes are like Properties:** Objects have attributes, which are like their properties. For instance, a car object might have attributes like "color," "brand," and "speed."

  - **Methods are like Actions:** Objects can also do things, and these actions are defined using methods. In our car example, a method could be "start" to make the car go.

**Here's a simpler example in Python**

```python
# Define a class called "Cat"
class Cat:
    def __init__(self, name, color):
        self.name = name   # "name" is an attribute
        self.color = color

    def meow(self):
        return f"{self.name} says Meow!"  # "meow" is a method

# Create a cat object
my_cat = Cat("Whiskers", "gray")

# Access attributes and call methods
print(my_cat.name)     # Output: Whiskers
print(my_cat.color)    # Output: gray
print(my_cat.meow())   # Output: Whiskers says Meow!
```
### 17. Error Handling in Python

Error handling is a crucial aspect of programming that allows you to gracefully handle unexpected situations or errors that may occur during the execution of a program. Python provides a robust error handling mechanism through exceptions. Here's an explanation of error handling in Python:

  - **Syntax Errors:** These occur when the code violates the rules of the Python language. They are typically detected by the Python interpreter during compilation and prevent the code from running. Common examples include missing colons, unmatched parentheses, and misspelled keywords.

```python
   if x = 5:  # SyntaxError: invalid syntax
       print("Hello")
```
  - **Runtime Errors (Exceptions):** These occur during program execution when something unexpected happens. Python provides a wide range of built-in exceptions to handle different types of errors. Common exceptions include:
   
     - `ZeroDivisionError`: Raised when attempting to divide by zero.
     - `TypeError`: Raised when an operation is performed on an inappropriate data type.
     - `ValueError`: Raised when a function receives an argument of the correct data type but with an inappropriate value.
     - `FileNotFoundError`: Raised when attempting to open or manipulate a file that doesn't exist.
     - `IndexError`: Raised when trying to access an index that is out of range in a sequence.
     - `KeyError`: Raised when trying to access a dictionary key that doesn't exist.
     - `NameError`: Raised when using a variable or name that is not defined.
```python
   try:
       result = 10 / 0  # ZeroDivisionError
   except ZeroDivisionError as e:
       print(f"Error: {e}")
```
- **Python Exception Handling:** Python provides a structured way to handle exceptions using the `try`, `except`, `else`, and `finally` blocks.

     - `try`: This block contains the code that might raise an exception.
    - `except`: This block is executed when an exception is raised. You can specify the type of exception to catch.
    - `else`: This block is executed if no exception is raised in the `try` block.
    - `finally`: This block is always executed, regardless of whether an exception occurred or not. It's often used for cleanup operations.

**Example:**

```python
try:
    x = 10 / 0  # This will raise a ZeroDivisionError
except ZeroDivisionError as e:
    print(f"Error: {e}")
else:
    print("No exception occurred")
finally:
    print("Finally block always executes")
```
