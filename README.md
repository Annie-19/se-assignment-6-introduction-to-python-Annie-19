[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15338083&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high level programming language known for its simplicity, readability and versatility.
KEY FEATURES OF PYTHON:
1.General-Purpose: Python can be used for a wide range of applications, including web development, data analysis, scientific computing, automation, machine learning, and more.
2.Dynamic Typing: Python is dynamically typed, meaning you don’t need to declare variable types explicitly. The interpreter infers the type at runtime.
3.Rich Standard Library: Python comes with an extensive standard library that provides modules and functions for various tasks, from file I/O to networking.
4.Third-Party Packages: The Python ecosystem includes a vast collection of third-party packages (e.g., NumPy, pandas, Django) that extend its capabilities.
5.Indentation-Based Syntax: Unlike languages that use braces or semicolons, Python uses indentation (whitespace) to define code blocks. This enforces consistent and readable code.
6.Cross-Platform: Python runs on various platforms (Windows, macOS, Linux) without modification.
7.Community and Documentation: Python has a large and active community, making it easy to find resources, libraries, and support.
EXAMPLE OF CASES WHERE PYTHON IS EFFECTIVE:
1.Web Development:
Python is commonly used for building web applications. Frameworks like Django and Flask make it easy to create robust, scalable, and maintainable web services.
Web scraping and data extraction tasks are also popular in Python due to libraries like Beautiful Soup and Scrapy.
2.Data Science and Machine Learning:
Python is the go-to language for data science and machine learning. Libraries like NumPy, pandas, and scikit-learn provide powerful tools for data manipulation, analysis, and modeling.
TensorFlow and PyTorch are widely used for deep learning and neural network development.
3.Scientific Computing:
Scientists and researchers use Python for simulations, numerical analysis, and solving complex mathematical problems.
SciPy, SymPy, and matplotlib are essential libraries for scientific computing.
4.Automation and Scripting:
Python’s simplicity and readability make it ideal for writing scripts and automating repetitive tasks.
System administration, file handling, and batch processing benefit from Python scripts.
5.Game Development:
Although not as common as other languages, Python is used for game development. Libraries like Pygame provide a foundation for creating 2D games.
6.Desktop Applications:
Python can be used to build cross-platform desktop applications using frameworks like PyQt or wxPython.
Tools like PyInstaller and cx_Freeze package Python applications into standalone executables.
7.Natural Language Processing (NLP):
Python’s NLTK and spaCy libraries enable developers to work with text data, perform sentiment analysis, and build chatbots.
8.GIS and Mapping:
Python is used in geographic information systems (GIS) for spatial data analysis, mapping, and visualization.
Libraries like geopandas and folium simplify GIS tasks.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

1.Install Python on Windows 11:
Go to the official Python website  and download the latest version of Python.
Run the downloaded installer.
During installation, check the box that says “Add Python to PATH.”
Wait for the installation to complete.
2.Verify the Installation:
Open Command Prompt and type:
python --version
If successful, you’ll see the Python version displayed.
3.Set Up a Virtual Environment:
Decide where you want to create your virtual environment (e.g., on your desktop).
Open Command Prompt and navigate to that directory.
Create the virtual environment using:
python -m venv myenv
Replace “myenv” with your desired environment name.
Activate the virtual environment


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

print("Hello, World!")

The print() function is used to display text or values in the console.
The "Hello, World!" is a string.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

1.Integers (int):
Represent whole numbers (positive, negative, or zero).
Example: 42, -10, 0.
2.Floating-Point Numbers (float):
Represent decimal numbers with fractional parts.
Example: 3.14, -0.5, 2.718.
3.Strings (str):
Represent sequences of characters (text).
Enclosed in single (') or double (") quotes.
Example: "Hello, World!", 'Python'.
4..Boolean (bool):
Represent truth values (True or False).
Used for logical operations and control flow.
Example: True, False.
5.Lists (list):
Ordered collections of items (mutable).
Enclosed in square brackets ([]).
Example: [1, 2, 3], ['apple', 'banana', 'cherry'].
6.Tuples (tuple):
Similar to lists but immutable (cannot be modified after creation).
Enclosed in parentheses (()).
Example: (10, 20, 30).
7..Dictionaries (dict):
Key-value pairs (associative arrays).
Enclosed in curly braces ({}).
Example: {'name': 'Alice', 'age': 25}.
8.Sets (set):
Unordered collections of unique elements.
Enclosed in curly braces ({}) or created using set().
Example: {1, 2, 3}, {'apple', 'banana'}.
9.None (NoneType):
Represents absence of a value (similar to null).
Used for initialization or indicating missing data.
# Integer variable
age = 20

# Floating-point variable
pi = 5.14

# String variable
name = "Esther"

# Boolean variable
is_student = True

# List variable
fruits = ["apple", "banana", "mango"]

# Dictionary variable
person_info = {"name": "Anne", "age": 20}

# Tuple variable
coordinates = (10, 20)

# Set variable
unique_numbers = {1, 2, 3}

# Printing values
print(f"Name: {name}")
print(f"Age: {age}")
print(f"Is student? {is_student}")
print(f"Fruits: {fruits}")
print(f"Coordinates: {coordinates}")
print(f"Unique numbers: {unique_numbers}")

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

USE OF CONDITIONAL STATEMENTS AND LOOPS IN PYTHON
1.Conditional Statements:
Conditional statements allow you to execute different code blocks based on certain conditions.
The most common conditional statements are:
if: Executes a block of code if a condition is true.
elif (short for “else if”): Used for additional conditions.
else: Executes a block of code if none of the previous conditions are true.
2.Loops:
Loops allow you to repeat a block of code multiple times.
Two main types of loops in Python:
for loop: Iterates over a sequence (e.g., a list, tuple, or string).
while loop: Repeats as long as a condition is true.
EXAMPLE OF if-else
age = 18 
if age >= 18:
   print("You can join college!")
else:
     print("Go back to high school.")
EXAMPLE OF for loop
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(f"Found a {fruit}!")



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions are reusable blocks of code that perform specific tasks.
WHY FUNCTIONS ARE USEFULL
1.Modularity:
Functions break down complex tasks into smaller, manageable parts.
You can create separate functions for different functionalities (e.g., data processing, file I/O, calculations).
2.Code Reusability:
Once defined, you can call a function multiple times from different parts of your program.
Saves effort by avoiding duplicate code.
3.Abstraction:
Functions abstract away implementation details.
Users of the function only need to know what it does, not how it does it.
4.Readability:
Well-named functions make code more readable.
Descriptive function names convey intent.
5.Parameterization:
Functions can accept input parameters (arguments).
You can customize behavior by passing different values.
6.Return Values:
Functions can return results or data.
Useful for calculations, transformations, or data retrieval.
def add_numbers(a, b):
    """Returns the sum of two numbers."""
    return a + b

# Example usage:
result = add_numbers(5, 3)
print(f"Sum: {result}")
n this example:

The add_numbers function accepts two arguments (a and b).
It calculates their sum using the + operator.
The result is stored in the result variable and printed to the console.


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

1.Lists (list):
Ordered Collection:
Lists are ordered, meaning the elements maintain their order of insertion.
Accessing elements by index (position) is straightforward.
Mutable:
You can modify, add, or remove elements from a list after creation.
Homogeneous or Heterogeneous:
Lists can contain elements of different data types (e.g., strings, numbers, other lists).
Syntax:
Defined using square brackets ([]).
Example: my_list = [1, 2, 3]
2.Dictionaries (dict):
Key-Value Pairs:
Dictionaries store data as key-value pairs.
Each key maps to a corresponding value.
Unordered:
Dictionaries are unordered (no fixed order of elements).
Access elements by their keys, not by position.
Mutable:
You can add, modify, or delete key-value pairs.
# Create a list of numbers
numbers = [1, 2, 3, 4, 5]

# Create a dictionary with key-value pairs
person = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}

# Accessing elements:
print(f"Third number in the list: {numbers[2]}")
print(f"Age of {person['name']}: {person['age']}")

# Modifying elements:
numbers[1] = 10
person["city"] = "Los Angeles"

# Adding elements:
numbers.append(6)
person["gender"] = "Female"

# Removing elements:
del numbers[3]
person.pop("age")

# Display updated lists and dictionaries:
print("Updated numbers:", numbers)
print("Updated person info:", person)

In this script:
We create a list called numbers and a dictionary called person.
We demonstrate accessing, modifying, adding, and removing elements from both data structures.


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling in Python refers to the practice of managing and responding to runtime errors or exceptional situations that may occur during program execution. It allows you to gracefully handle errors, prevent program crashes, and provide meaningful feedback to users.
def divide(a, b):
    try:
        result = a / b
        print(f"Result: {result}")
    except ZeroDivisionError:
        print("Error: Cannot divide by zero")
    finally:
        print("Cleanup: This always runs")

# Example usage:
divide(10, 2)  # Normal division
divide(5, 0)   # Division by zero



9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
1.Modules:
A module is a single file containing Python code.
It can include functions, classes, variables, and other definitions.
Modules allow you to organize and reuse code by breaking it into smaller, manageable pieces.
2.Packages:
A package is a collection of related modules organized in directories.
Packages allow you to create a hierarchical structure for your code
HOW TO IMPORT AND USE A MODULE IN YOUR SCRIPT
1.Create or Locate the Module:
First, ensure you have a Python module (a .py file) containing the code you want to use.
You can create your own module or use an existing one.
2.Import the Module:
In your script, use the import statement to bring the module into your code.
3.Access Functions or Variables from the Module:
Once imported, you can use functions, classes, or variables defined in the module.
4.Use the Imported Code:
You can now use the functions or variables from the module in your script.
EXAMPLE USING MATH MODULE
import math

# Example : Calculate the square root
number = 25
square_root = math.sqrt(number)
print(f"Square root of {number} is {square_root:.2f}")



10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
# read_file.py
try:
    with open("my_file.txt", "r") as file:
        content = file.read()
        print(content)
except FileNotFoundError:
    print("File not found. Please check the filename.")
# write_file.py
my_strings = ["Hello", "World", "Python", "File I/O"]

try:
    with open("output.txt", "w") as file:
        for string in my_strings:
            file.write(string + "\n")
    print("Data written successfully!")
except Exception as e:
    print(f"Error writing to file: {e}")

Reading from a Text File:
Use methods like read(), readline(), or readlines() to retrieve data from a text file.
Writing to a Text File:
Use the write() method to store data into a file.


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


