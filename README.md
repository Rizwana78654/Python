
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

<body>
<div class="section">
    <h1> Python Programming</h1>
    <p>
        <strong>Python programming</strong> is the process of writing instructions using the Python
        programming language to communicate with a computer.
        Python programming is widely used in areas such as
            web development, data analysis, artificial intelligence,
            automation, and software development.
        Python is one of the most popular programming languages in the world.
        It is widely used in both education and industry because of its simplicity,
        flexibility, and powerful features.
    </p>
</div>

</body>
</html>

<h2> Index</h2>
<ul>
    <li><a href="#basic">Basic Python Concepts</a></li>
    <li><a href="#intermediate">Intermediate Python Concepts</a></li>
    <li><a href="#advanced">Advanced Python Concepts</a></li>
</ul>
<h2 id="basic"> Basic Python Concepts</h2>
<ul>
    <li>Variables </li>
    <li> Data types</li>
    <li> Type conversions </li>
    <li>Operators</li>
    <li>Libraries</li>
    <li> Built -in- Functions
    <li>Strings</li>
    <li>Lists</li>
    <li> Tuples </li>
    <li>sets</li>
    <li>dictionaries</li>
</ul>
<hr>

<h2 id="intermediate"> Intermediate Python Concepts</h2>
<ul>
    <li>Looping statements</li>
    <li>control statements </li>
    <li> Functions</li>
    <li>Lambda Functions</li>
    <li>List and Dictionary Comprehensions</li>
    <li>Recursions</li>
    <li>File Handling</li>
    <li>Exception Handling</li>
    <li>Object-Oriented Programming (OOP)</li>
</ul>
<h2 id="advanced"> Advanced Python Concepts</h2>
<ul>
    <li>Exception Handling</li>
    <li>Class</li>
    <li>Object</li>
    <li>self</li>
    <li>Constructor</li>
    <li>Inheritance</li>
    <li>Polymorphism</li>
    <li>Abstraction</li>
    <li>Encapsulation</li>
    <li>Multithreading and Multiprocessing</li>
    <li>API Integration</li>
    <li>Database Connectivity</li>
    <li>Data Science and Machine Learning</li>
</ul>


<h1>1️. Basic Python</h1>
<hr>

<p>
Basic Python concepts form the foundation of Python programming.
These concepts are essential for beginners to understand how Python works.
</p>

## Installation of Python

1. Open a web browser
2. Go to the official Python website:
   (https://www.python.org)
3. Click on **Downloads**
4. Choose the latest **Python 3** version for your operating system

<pre>
python --version
</pre>

<h2> Introduction to python</h2>
<p>
<b>Python</b> is a high-level, interpreted, and general-purpose programming language.
It was created by <b>Guido van Rossum</b> and released in <b>1991</b>.
Python is known for its simple syntax and readability, making it easy to learn
for beginners.

    
   Python focuses on code readability and allows programmers to write fewer lines of code compared to many other languages. 
</p>

<hr>

<h2> Features of Python</h2>
<ul>
    <li>Easy to learn and use</li>
    <li>High-level language</li>
    <li>Interpreted language</li>
    <li>Object-oriented</li>
    <li>Platform independent</li>
    <li>Large standard library</li>
    <li>Open-source and free</li>
</ul>

<hr>

<h2> Why Learn Python?</h2>
<p>
Python is one of the most popular programming languages in the world.
It is widely used in many fields due to its simplicity and power.
</p>

<ul>
    <li>Web Development</li>
    <li>Data Science and Analytics</li>
    <li>Machine Learning & AI</li>
    <li>Automation and Scripting</li>
    <li>Game Development</li>
    <li>Desktop Applications</li>
</ul>

<hr>

<h2> First Python Program</h2>

<pre>
print("Hello, World!")
</pre>

<p>
The <b>print()</b> function is used to display output on the screen.
</p>

<hr>

<h2> Python Syntax Example</h2>

<pre>
name = "Python"
version = 3.12

print("Language:", name)
print("Version:", version)
</pre>

<hr>

<h2> Applications of Python</h2>
<ul>
    <li>Web Applications</li>
    <li>Scientific Computing</li>
    <li>Cyber Security</li>
    <li>Cloud Computing</li>
    <li>Internet of Things (IoT)</li>
</ul>

<h1> Comments in Python</h1>

<h2> What are Comments?</h2>
<p>
Comments in Python are lines of text used to explain the code.
They are ignored by the Python interpreter and do not affect program execution.
</p>

<h2> Why are Comments Important?</h2>
<ul>
  <li>Improve code readability</li>
  <li>Explain complex logic</li>
  <li>Make code easy to maintain</li>
  <li>Helpful for teamwork</li>
</ul>

<h2> Types of Comments in Python</h2>

<h3>1️. Single-Line Comments</h3>
<p>
Single-line comments start with the <code>#</code> symbol.
</p>

<pre><code>
# This is a single-line comment
print("Hello, Python")
</code></pre>

<h3>2️. Inline Comments</h3>
<p>
Inline comments are written on the same line as the code.
</p>

<pre><code>
x = 10  # Assigning value to x
</code></pre>

<h3>3️. Multi-Line Comments</h3>
<p>
Python does not have a special multi-line comment syntax.
Triple quotes are commonly used for documentation.
</p>

<pre><code>
"""
This is a multi-line comment
Used to explain multiple lines
"""
print("Python Comments")
</code></pre>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

</head>
<body>

<h1>Print Statement in Python</h1>

<h2>What is print()?</h2>
<p>
The <strong>print()</strong> function in Python is used to display output on the screen.
It is one of the most commonly used functions in Python programming.
</p>

<h2>Syntax</h2>
<pre>
print(value)
</pre>

<h2>Printing a String</h2>
<pre>
print("Hello, Python")
</pre>

<h2>Printing Variables</h2>
<pre>
name = "Python"
version = 3
print(name)
print(version)
</pre>

<h2>Printing Multiple Values</h2>
<pre>
a = 10
b = 20
print(a, b)
</pre>

<h2>Using sep Parameter</h2>
<pre>
print("Python", "Java", "C", sep=" | ")
</pre>

<h2>Using end Parameter</h2>
<pre>
print("Hello", end=" ")
print("World")
</pre>

<h2>Printing Expressions</h2>
<pre>
x = 5
y = 10
print(x + y)
</pre>


</body>
</html>

<html>
<head>
    <meta charset="UTF-8">
</head>

<body>

<h1> Variables in Python </h1>
<p>
  A variable is a name that stores a value in python .it works like a container that holds data such as numbers,strings,lists,etc.
<hr>

<h2> What is a Variable?</h2>
<p>
A <b>variable</b> is a name given to a memory location that stores a value.
Variables allow us to store data, reuse it, and modify it during program execution.
</p>

<p>
In simple words, a variable works like a <b>container</b> that holds data.
</p>

<hr>

<h2> Creating Variables in Python</h2>
<p>
In Python, variables are created when a value is assigned to them.
There is no need to declare the data type explicitly.
</p>

<h3>Syntax:</h3>
<pre>
variable_name = value
</pre>

<h3>Examples:</h3>
<pre>
x = 10
name = "Python"
price = 99.99
is_active = True
</pre>

<hr>

<h2> Dynamic Typing in Python</h2>
<p>
Python is a <b>dynamically typed language</b>.
This means the type of a variable can change during program execution.
</p>

<pre>
x = 10
print(x)

x = "Hello"
print(x)
</pre>

<hr>

<h2> Rules for Naming Variables</h2>
<ul>
    <li>Variable names must start with a letter or underscore (_)</li>
    <li>They can contain letters, numbers, and underscores</li>
    <li>They cannot start with a number</li>
    <li>No spaces or special characters are allowed</li>
    <li>Python keywords cannot be used as variable names</li>
</ul>

<h3>Valid Variable Names:</h3>
<pre>
age
_student
total_marks
</pre>

<h3>Invalid Variable Names:</h3>
<pre>
2value
total-marks
class
</pre>

<hr>

<h2> Multiple Assignment</h2>
<p>
Python allows assigning multiple values to multiple variables in a single line.
</p>

<pre>
a, b, c = 1, 2, 3
</pre>

<p>
Assigning the same value to multiple variables:
</p>

<pre>
x = y = z = 100
</pre>

<hr>

<h2> Variable Reassignment</h2>
<p>
The value of a variable can be changed after it is created.
</p>

<pre>
count = 5
count = count + 1
print(count)
</pre>

<hr>

<h2> Variable Scope</h2>

<h3>Local Variable</h3>
<p>
A local variable is defined inside a function and can be used only within that function.
</p>

<pre>
def show():
    x = 10
    print(x)
</pre>

<h3>Global Variable</h3>
<p>
A global variable is defined outside a function and can be accessed anywhere in the program.
</p>

<pre>
x = 20

def display():
    print(x)
</pre>

<hr>

<h2> Deleting Variables</h2>
<p>
Python provides the <b>del</b> keyword to delete a variable.
</p>

<pre>
x = 50
del x
</pre>

<hr>

<h2> Checking Variable Type</h2>
<p>
The <b>type()</b> function is used to check the data type of a variable.
</p>

<pre>
x = 10
print(type(x))
</pre>

<hr>

<h2> Constants in Python</h2>
<p>
Python does not have true constants.
By convention, variables written in uppercase are treated as constants.
</p>

<pre>
PI = 3.14
MAX_VALUE = 100
</pre>

<hr>

<h2> Why Variables Are Important?</h2>
<ul>
    <li>Store and manage data</li>
    <li>Make programs flexible</li>
    <li>Improve code readability</li>
    <li>Enable reuse of values</li>
</ul>


<html>
<head>
    <meta charset="UTF-8">
  
</head>

<body>

<h1> Data Types in Python </h1>
<hr>

<h2> What is a Data Type?</h2>
<p>
A <b>data type</b> specifies the type of value that a variable can store.
It tells Python how much memory to allocate and what operations can be performed on the data.

</p>

<p>
Python automatically assigns a data type based on the value stored in a variable.
</p>

<hr>

<h2> Built-in Data Types in Python</h2>
<p>
Python provides several built-in data types which are grouped into categories:
</p>

<ul>
    <li>Numeric Data Types</li>
    <li>Text Data Type</li>
    <li>Boolean Data Type</li>
    <li>Sequence Data Types</li>
    <li>Set Data Types</li>
    <li>Mapping Data Type</li>
    <li>None Data Type</li>
</ul>

<hr>

<h2>1️. Numeric Data Types</h2>

<h3> int (Integer)</h3>
<p>
The <b>int</b> data type stores whole numbers (positive, negative, or zero).
</p>

<pre>
a = 10
b = -45
c = 0
</pre>

<hr>

<h3> float</h3>
<p>
The <b>float</b> data type stores decimal (fractional) numbers.
</p>

<pre>
x = 3.14
y = 99.99
</pre>

<hr>

<h3> complex</h3>
<p>
The <b>complex</b> data type stores numbers with real and imaginary parts.
The imaginary part is represented using <b>j</b>.
</p>

<pre>
z = 2 + 3j
</pre>

<hr>

<h2>2. Text Data Type</h2>

<h3> str (String)</h3>
<p>
The <b>str</b> data type stores a sequence of characters.
Strings can be enclosed in single quotes or double quotes.
</p>

<pre>
name = "Python"
city = 'Hyderabad'
</pre>

<h4>String Operations:</h4>
<pre>
s = "Python"
print(s[0])     # P
print(len(s))   # 6
</pre>

<hr>

<h2>3️. Boolean Data Type</h2>

<h3> bool</h3>
<p>
The <b>bool</b> data type stores only two values: <b>True</b> or <b>False</b>.
It is mainly used in decision making and conditions.
</p>

<pre>
is_login = True
is_admin = False
</pre>

<hr>

<h2>4️. Sequence Data Types</h2>

<h3> list</h3>
<p>
A <b>list</b> is an ordered and mutable collection of elements.
Elements can be changed after creation.
</p>

<pre>
marks = [80, 85, 90]
marks[0] = 95
</pre>

<hr>

<h3> tuple</h3>
<p>
A <b>tuple</b> is an ordered but immutable collection.
Once created, elements cannot be modified.
</p>

<pre>
colors = ("red", "green", "blue")
</pre>

<hr>

<h3> range</h3>
<p>
The <b>range</b> data type represents a sequence of numbers.
It is commonly used with loops.
</p>

<pre>
r = range(1, 6)
</pre>

<hr>

<h2>5️. Set Data Types</h2>

<h3> set</h3>
<p>
A <b>set</b> is an unordered collection of unique elements.
Duplicate values are automatically removed.
</p>

<pre>
nums = {1, 2, 3, 3}
print(nums)   # {1, 2, 3}
</pre>

<hr>

<h3> frozenset</h3>
<p>
A <b>frozenset</b> is an immutable version of a set.
</p>

<pre>
fs = frozenset([1, 2, 3])
</pre>

<hr>

<h2>6️. Mapping Data Type</h2>

<h3> dict (Dictionary)</h3>
<p>
A <b>dictionary</b> stores data in key-value pairs.
Keys must be unique.
</p>

<pre>
student = {
    "name": "Rizwana",
    "age": 21,
    "course": "Python"
}
</pre>

<hr>

<h2>7️. None Data Type</h2>

<h3> NoneType</h3>
<p>
The <b>None</b> data type represents the absence of a value.
</p>

<pre>
result = None
</pre>

<hr>

<h2> Mutable vs Immutable Data Types</h2>

<h3>Mutable (Can be Changed)</h3>
<ul>
    <li>list</li>
    <li>set</li>
    <li>dict</li>
</ul>

<h3>Immutable (Cannot be Changed)</h3>
<ul>
    <li>int</li>
    <li>float</li>
    <li>str</li>
    <li>tuple</li>
    <li>frozenset</li>
</ul>

<hr>

<h2> Checking Data Type</h2>
<p>
The <b>type()</b> function is used to check the data type of a variable.
</p>

<pre>
x = 10
print(type(x))
</pre>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>
<body>

<h1>Type Conversion Examples in Python</h1>

<p>
Type conversion means changing one data type into another.
Python provides built-in functions to perform these conversions.
</p>

<hr>

<h2>1. Integer to Float</h2>
<pre>
a = 10
b = float(a)
print(b)
</pre>

<p>Output: <strong>10.0</strong></p>

<hr>

<h2>2. Float to Integer</h2>
<pre>
x = 5.9
y = int(x)
print(y)
</pre>

<p>
Note: Decimal part is removed (not rounded).
</p>

<p>Output: <strong>5</strong></p>

<hr>

<h2>3. Integer to String</h2>
<pre>
num = 100
text = str(num)
print(text)
</pre>

<p>Output: <strong>"100"</strong></p>

<hr>

<h2>4. String to Integer</h2>
<pre>
value = "25"
number = int(value)
print(number)
</pre>

<p>Output: <strong>25</strong></p>

<hr>

<h2>5. String to Float</h2>
<pre>
data = "3.14"
f = float(data)
print(f)
</pre>

<p>Output: <strong>3.14</strong></p>

<hr>

<h2>6. Float to String</h2>
<pre>
price = 9.5
text = str(price)
print(text)
</pre>

<p>Output: <strong>"9.5"</strong></p>

</body>
</html>


<html>
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1> Operators in Python</h1>
<hr>

<p>
<b>Operators</b> are special symbols used to perform operations on values and variables.
Python supports different types of operators.
</p>

<hr>

<h2>1️. Arithmetic Operators</h2>
<p>Used to perform mathematical operations.</p>

<table border="1" cellpadding="8">
<tr>
    <th>Operator</th>
    <th>Description</th>
    <th>Example</th>
</tr>
<tr>
    <td>+</td>
    <td>Addition</td>
    <td>a + b</td>
</tr>
<tr>
    <td>-</td>
    <td>Subtraction</td>
    <td>a - b</td>
</tr>
<tr>
    <td>*</td>
    <td>Multiplication</td>
    <td>a * b</td>
</tr>
<tr>
    <td>/</td>
    <td>Division</td>
    <td>a / b</td>
</tr>
<tr>
    <td>%</td>
    <td>Modulus</td>
    <td>a % b</td>
</tr>
<tr>
    <td>**</td>
    <td>Exponent</td>
    <td>a ** b</td>
</tr>
<tr>
    <td>//</td>
    <td>Floor Division</td>
    <td>a // b</td>
</tr>
</table>

<pre>
a = 10
b = 3
print(a + b)
print(a % b)
</pre>

<hr>

<h2>2️. Assignment Operators</h2>
<p>Used to assign values to variables.</p>

<pre>
x = 5
x += 3   # x = x + 3
x -= 2   # x = x - 2
</pre>

<hr>

<h2>3️. Comparison Operators</h2>
<p>Used to compare two values. Result is True or False.</p>

<table border="1" cellpadding="8">
<tr>
    <th>Operator</th>
    <th>Description</th>
</tr>
<tr>
    <td>==</td>
    <td>Equal to</td>
</tr>
<tr>
    <td>!=</td>
    <td>Not equal</td>
</tr>
<tr>
    <td>></td>
    <td>Greater than</td>
</tr>
<tr>
    <td><</td>
    <td>Less than</td>
</tr>
<tr>
    <td>>=</td>
    <td>Greater than or equal to</td>
</tr>
<tr>
    <td><=</td>
    <td>Less than or equal to</td>
</tr>
</table>

<pre>
a = 10
b = 5
print(a > b)
print(a == b)
</pre>

<hr>

<h2>4️. Logical Operators</h2>
<p>Used to combine conditional statements.</p>

<ul>
    <li><b>and</b> – True if both conditions are true</li>
    <li><b>or</b> – True if at least one condition is true</li>
    <li><b>not</b> – Reverses the result</li>
</ul>

<pre>
a = 10
b = 5
print(a > 5 and b < 10)
</pre>

<hr>

<h2>5️. Identity Operators</h2>
<p>Used to check if two variables refer to the same object.</p>

<ul>
    <li><b>is</b></li>
    <li><b>is not</b></li>
</ul>

<pre>
a = 5
b = 5
print(a is b)
</pre>

<hr>

<h2>6️. Membership Operators</h2>
<p>Used to check if a value exists in a sequence.</p>

<ul>
    <li><b>in</b></li>
    <li><b>not in</b></li>
</ul>

<pre>
list1 = [1, 2, 3]
print(2 in list1)
</pre>

<hr>

<h2>7️. Bitwise Operators</h2>
<p>Used to perform bit-level operations.</p>

<pre>
a = 5   # 101
b = 3   # 011
print(a & b)
print(a | b)
</pre>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>
<body>

<h1>Bitwise Operators in Python</h1>

<p>
<strong>Bitwise operators</strong> are used to perform operations directly on the
binary (bit-level) representation of numbers.
</p>

<hr>

<h2>List of Bitwise Operators</h2>

<table border="1" cellpadding="8">
    <tr>
        <th>Operator</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>&amp;</td>
        <td>Bitwise AND</td>
        <td>Sets each bit to 1 if both bits are 1</td>
    </tr>
    <tr>
        <td>|</td>
        <td>Bitwise OR</td>
        <td>Sets each bit to 1 if one of the bits is 1</td>
    </tr>
    <tr>
        <td>^</td>
        <td>Bitwise XOR</td>
        <td>Sets each bit to 1 if bits are different</td>
    </tr>
    <tr>
        <td>~</td>
        <td>Bitwise NOT</td>
        <td>Inverts all the bits</td>
    </tr>
    <tr>
        <td>&lt;&lt;</td>
        <td>Left Shift</td>
        <td>Shifts bits to the left</td>
    </tr>
    <tr>
        <td>&gt;&gt;</td>
        <td>Right Shift</td>
        <td>Shifts bits to the right</td>
    </tr>
</table>

<hr>

<h2>Examples of Bitwise Operators</h2>

<h3>Bitwise AND (&amp;)</h3>
<pre>
a = 5   # 0101
b = 3   # 0011
print(a & b)
</pre>
<p>Output: <strong>1</strong></p>

<hr>

<h3>Bitwise OR (|)</h3>
<pre>
a = 5   # 0101
b = 3   # 0011
print(a | b)
</pre>
<p>Output: <strong>7</strong></p>

<hr>

<h3>Bitwise XOR (^)</h3>
<pre>
a = 5
b = 3
print(a ^ b)
</pre>
<p>Output: <strong>6</strong></p>

<hr>

<h3>Bitwise NOT (~)</h3>
<pre>
a = 5
print(~a)
</pre>
<p>Output: <strong>-6</strong></p>

<hr>

<h3>Left Shift (&lt;&lt;)</h3>
<pre>
a = 5
print(a << 1)
</pre>
<p>Output: <strong>10</strong></p>

<hr>

<h3>Right Shift (&gt;&gt;)</h3>
<pre>
a = 5
print(a >> 1)
</pre>
<p>Output: <strong>2</strong></p>

<hr>

<h2>Why Bitwise Operators are Used?</h2>
<ul>
    <li>Low-level programming</li>
    <li>Performance optimization</li>
    <li>Cryptography</li>
    <li>Network programming</li>
</ul>

<hr>

<h2>Conclusion</h2>
<p>
Bitwise operators work at the binary level and are useful for efficient
and fast computations in Python.
</p>

</body>
</html>

<body>

<h1> Libraries in Python</h1>
<hr>

<h2> What is a Library?</h2>
<p>
A <b>library</b> in Python is a collection of pre-written code (modules and packages)
that helps developers perform common tasks easily without writing code from scratch.
</p>

<hr>

<h2> Why Use Libraries?</h2>
<ul>
    <li>Save time and effort</li>
    <li>Reduce code length</li>
    <li>Improve productivity</li>
    <li>Provide ready-made functions</li>
</ul>

<hr>

<h2> Types of Libraries in Python</h2>

<h3>1️. Built-in Libraries</h3>
<p>
These libraries come pre-installed with Python.
</p>

<ul>
    <li><b>math</b> – Mathematical operations</li>
    <li><b>random</b> – Random number generation</li>
    <li><b>datetime</b> – Date and time handling</li>
    <li><b>os</b> – Operating system interaction</li>
    <li><b>sys</b> – System-specific parameters</li>
</ul>

<h4>Example:</h4>
<pre>
import math
print(math.sqrt(16))
</pre>

<hr>

<h3>2️. External (Third-Party) Libraries</h3>
<p>
These libraries are not included by default and must be installed using <b>pip</b>.
</p>

<ul>
    <li><b>numpy</b> – Numerical computing</li>
    <li><b>pandas</b> – Data analysis</li>
    <li><b>matplotlib</b> – Data visualization</li>
    <li><b>requests</b> – HTTP requests</li>
</ul>

<h4>Installation:</h4>
<pre>
pip install numpy
</pre>

<hr>

<h3>3️. User-Defined Libraries</h3>
<p>
Libraries created by the user to reuse code in multiple programs.
</p>

<h4>Example:</h4>
<pre>
# mylib.py
def add(a, b):
    return a + b
</pre>

<pre>
import mylib
print(mylib.add(5, 3))
</pre>

<hr>

<h2> Importing Libraries in Python</h2>

<h4>Import entire library:</h4>
<pre>
import math
</pre>

<h4>Import specific function:</h4>
<pre>
from math import sqrt
</pre>

<h4>Import with alias:</h4>
<pre>
import numpy as np
</pre>

<hr>

<h2> Popular Python Libraries</h2>
<table border="1" cellpadding="8">
<tr>
    <th>Library</th>
    <th>Usage</th>
</tr>
<tr>
    <td>numpy</td>
    <td>Scientific computing</td>
</tr>
<tr>
    <td>pandas</td>
    <td>Data analysis</td>
</tr>
<tr>
    <td>matplotlib</td>
    <td>Data visualization</td>
</tr>
<tr>
    <td>requests</td>
    <td>Web requests</td>
</tr>
</table>
<html>
<head>
    <meta charset="UTF-8">
</head>

<body>

<h1> Built-in Functions in Python</h1>
<hr>

<h2> What are Built-in Functions?</h2>
<p>
<b>Built-in functions</b> are predefined functions provided by Python.
They are always available and do not require any import.
</p>

<hr>

<h2> Why Use Built-in Functions?</h2>
<ul>
    <li>Save time and effort</li>
    <li>Reduce code length</li>
    <li>Improve readability</li>
    <li>Increase efficiency</li>
</ul>

<hr>

<h2> Common Built-in Functions</h2>

<h3>1️. print()</h3>
<p>Displays output on the screen.</p>
<pre>
print("Hello Python")
</pre>

<hr>

<h3>2️. input()</h3>
<p>Takes input from the user.</p>
<pre>
name = input("Enter your name: ")
print(name)
</pre>

<hr>

<h3>3️ type()</h3>
<p>Returns the data type of a variable.</p>
<pre>
x = 10
print(type(x))
</pre>

<hr>

<h3>4️. len()</h3>
<p>Returns the length of a string, list, or tuple.</p>
<pre>
text = "Python"
print(len(text))
</pre>

<hr>

<h3>5️. int(), float(), str()</h3>
<p>Used for type conversion.</p>
<pre>
a = int("10")
b = float("3.5")
c = str(100)
</pre>

<hr>

<h3>6️. max() and min()</h3>
<p>Returns maximum and minimum values.</p>
<pre>
numbers = [10, 20, 30]
print(max(numbers))
print(min(numbers))
</pre>

<hr>

<h3>7️. sum()</h3>
<p>Returns the sum of elements.</p>
<pre>
nums = [1, 2, 3]
print(sum(nums))
</pre>

<hr>

<h3>8️.abs()</h3>
<p>Returns absolute value.</p>
<pre>
print(abs(-10))
</pre>

<hr>

<h3>9️. round()</h3>
<p>Rounds a floating number.</p>
<pre>
print(round(3.567, 2))
</pre>

<hr>

<h3> 10. sorted()</h3>
<p>Returns a sorted list.</p>
<pre>
nums = [3, 1, 4, 2]
print(sorted(nums))
</pre>

<hr>

<h2> Boolean Built-in Functions</h2>

<h3>any()</h3>
<pre>
print(any([0, 1, 0]))
</pre>

<h3>all()</h3>
<pre>
print(all([1, 2, 3]))
</pre>

<hr>

<h2> Example Program</h2>
<pre>
name = input("Enter name: ")
marks = [80, 90, 85]

print("Name:", name)
print("Total:", sum(marks))
print("Max:", max(marks))
print("Length of name:", len(name))
</pre>

<hr>
<html>
<head>
    <meta charset="UTF-8">
</head>

<body>

<h1> Strings in Python</h1>
<hr>

<h2> What is a String?</h2>
<p>
A <b>string</b> in Python is a sequence of characters enclosed in
single quotes (<b>' '</b>), double quotes (<b>" "</b>), or triple quotes.
</p>

<hr>

<h2> Creating Strings</h2>

<pre>
name = "Python"
city = 'Hyderabad'
message = """Welcome to Python Programming"""
</pre>

<hr>

<h2> Accessing String Characters</h2>
<p>Strings use indexing starting from <b>0</b>.</p>

<pre>
s = "Python"
print(s[0])   # P
print(s[-1])  # n
</pre>

<hr>

<h2> String Slicing</h2>

<pre>
s = "Python"
print(s[0:4])   # Pyth
print(s[:3])    # Pyt
print(s[2:])    # thon
</pre>

<hr>

<h2> String Operations</h2>

<h3>Concatenation</h3>
<pre>
a = "Hello"
b = "World"
print(a + " " + b)
</pre>

<h3>Repetition</h3>
<pre>
print("Hi " * 3)
</pre>

<hr>

<h2> String Methods</h2>

<ul>
    <li><b>upper()</b> – Converts to uppercase</li>
    <li><b>lower()</b> – Converts to lowercase</li>
    <li><b>strip()</b> – Removes spaces</li>
    <li><b>replace()</b> – Replaces text</li>
    <li><b>split()</b> – Splits string</li>
    <li><b>find()</b> – Finds position</li>
</ul>

<pre>
s = " Python Programming "
print(s.upper())
print(s.strip())
print(s.replace("Python", "Java"))
print(s.split())
</pre>

<hr>

<h2> String Formatting</h2>

<h3>Using f-strings</h3>
<pre>
name = "Rizwana"
age = 21
print(f"My name is {name} and my age is {age}")
</pre>

<hr>

<h2> Checking String Properties</h2>

<pre>
s = "Python123"
print(s.isalpha())
print(s.isdigit())
print(s.isalnum())
</pre>

<hr>

<h2> Looping Through a String</h2>

<pre>
s = "Python"
for ch in s:
    print(ch)
</pre>

<hr>

<h2> String is Immutable</h2>
<p>
Strings cannot be changed after creation.
</p>

<pre>
s = "Python"
# s[0] = "J"  ❌ Error
    </pre>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>

<body>

<h1> String Methods in Python</h1>
<hr>

<h2> What are String Methods?</h2>
<p>
<b>String methods</b> are built-in functions that operate on strings.
They help in manipulating and processing string data such as converting case,
searching text, splitting strings, and replacing values.
</p>

<p><b>Note:</b> Strings are <b>immutable</b>, so methods return a new string.</p>

<hr>

<h2> Common String Methods</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Method</th>
    <th>Description</th>
    <th>Example</th>
</tr>

<tr>
    <td>upper()</td>
    <td>Converts string to uppercase</td>
    <td>"python".upper()</td>
</tr>

<tr>
    <td>lower()</td>
    <td>Converts string to lowercase</td>
    <td>"PYTHON".lower()</td>
</tr>

<tr>
    <td>title()</td>
    <td>Capitalizes first letter of each word</td>
    <td>"hello world".title()</td>
</tr>

<tr>
    <td>capitalize()</td>
    <td>Capitalizes first character</td>
    <td>"python".capitalize()</td>
</tr>

<tr>
    <td>Title()</td>
    <td>title will convert each word first letter into capital remaining all are small</td>
    <td>" python ".tittle()</td>
</tr>

<tr>
    <td>lowerp()</td>
    <td>lower function is used to convert into small letter</td>
    <td>" python".lower()</td>
</tr>

<tr>
    <td>upper()</td>
    <td>upper function is used to convert into capital letter</td>
    <td>"python ".upper()</td>
</tr>

<tr>
    <td>isupper()</td>
    <td>will return the boolean outcome</td>
    <td>"python " .isupper()</td>
</tr>

<tr>
    <td> islower</td>
    <td>will return the boolean outcome</td>
    <td>"python ".islower()</td>
</tr>
<tr>
    <td>lstrip()</td>
    <td>Removes left spaces</td>
    <td>" python".lstrip()</td>
</tr>

<tr>
    <td>rstrip()</td>
    <td>Removes right spaces</td>
    <td>"python ".rstrip()</td>
</tr>
<tr>
    <td>join()</td>
    <td>Joins list elements into string</td>
    <td>"-".join(["a","b"])</td>
</tr>

<tr>
    <td>find()</td>
    <td>Finds index of substring</td>
    <td>"python".find("t")</td>
</tr>

<tr>
    <td>count()</td>
    <td>Counts occurrences</td>
    <td>"banana".count("a")</td>
</tr>

<tr>
    <td>startswith()</td>
    <td>Checks starting characters</td>
    <td>"python".startswith("py")</td>
</tr>

<tr>
    <td>endswith()</td>
    <td>Checks ending characters</td>
    <td>"python".endswith("on")</td>
</tr>

<tr>
    <td>isdigit()</td>
    <td>Checks if all characters are digits</td>
    <td>"123".isdigit()</td>
</tr>

<tr>
    <td>isalpha()</td>
    <td>Checks if all characters are alphabets</td>
    <td>"abc".isalpha()</td>
</tr>

<tr>
    <td>isalnum()</td>
    <td>Checks alphanumeric characters</td>
    <td>"abc123".isalnum()</td>
</tr>
<tr>
    <td>isalpha()</td>
    <td>do all  are alphabets</td>
    <td>"python ".isalpha()</td>
</tr>
<tr>
    <td>replace()</td>
    <td>replace a character</td>
    <td>"python ".replace()</td>
</tr>
  <tr>
    <td>strip()</td>
    <td>Removes leading and trailing spaces</td>
</tr>  
</table>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1>  Python Lists</h1>
<hr>

<h2> What is a List?</h2>
<p>
A <b>list</b> is a built-in data type in Python used to store multiple values in a single variable.
Lists are <b>ordered</b>, <b>mutable</b> (changeable), and allow <b>duplicate elements</b>.
</p>

<hr>

<h2> Creating a List</h2>

<pre>
numbers = [1, 2, 3, 4]
names = ["Python", "Java", "C"]
mixed = [1, "Hello", 3.5]
</pre>

<hr>

<h2> Accessing List Elements</h2>

<pre>
fruits = ["apple", "banana", "cherry"]

print(fruits[0])   # apple
print(fruits[-1])  # cherry
</pre>

<hr>

<h2> Modifying List Elements</h2>

<pre>
fruits[1] = "orange"
print(fruits)
</pre>

<hr>

<h2> List Built-in Methods</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Method</th>
    <th>Description</th>
    <th>Example</th>
</tr>

<tr>
    <td>append()</td>
    <td>Adds element at end</td>
    <td>list.append(10)</td>
</tr>

<tr>
    <td>insert()</td>
    <td>Adds element at index</td>
    <td>list.insert(1,5)</td>
</tr>

<tr>
    <td>extend()</td>
    <td>Adds multiple elements</td>
    <td>list.extend([1,2])</td>
</tr>

<tr>
    <td>remove()</td>
    <td>Removes specified element</td>
    <td>list.remove(3)</td>
</tr>

<tr>
    <td>pop()</td>
    <td>Removes element by index</td>
    <td>list.pop(1)</td>
</tr>

<tr>
    <td>clear()</td>
    <td>Removes all elements</td>
    <td>list.clear()</td>
</tr>

<tr>
    <td>index()</td>
    <td>Returns index of element</td>
    <td>list.index(5)</td>
</tr>

<tr>
    <td>count()</td>
    <td>Counts occurrences</td>
    <td>list.count(2)</td>
</tr>

<tr>
    <td>sort()</td>
    <td>Sorts the list</td>
    <td>list.sort()</td>
</tr>

<tr>
    <td>reverse()</td>
    <td>Reverses the list</td>
    <td>list.reverse()</td>
</tr>

<tr>
    <td>copy()</td>
    <td>Returns a copy of list</td>
    <td>list.copy()</td>
</tr>

</table>

<hr>

<h2> Example Program Using List Methods</h2>

<pre>
numbers = [10, 20, 30]

numbers.append(40)
numbers.insert(1, 15)
numbers.remove(20)
numbers.sort()

print(numbers)
</pre>

<hr>

<h2> List Built-in Functions</h2>

<ul>
    <li><b>len()</b> – Returns number of elements</li>
    <li><b>max()</b> – Returns maximum value</li>
    <li><b>min()</b> – Returns minimum value</li>
    <li><b>sum()</b> – Returns sum of elements</li>
    <li><b>type()</b> – Returns data type</li>
</ul>

<hr>

<h2> Mutable Nature of Lists</h2>

<pre>
a = [1, 2, 3]
a[0] = 100
print(a)
</pre>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1>  Python Tuples</h1>
<hr>

<h2> What is a Tuple?</h2>
<p>
A <b>tuple</b> is a built-in data type in Python used to store multiple values in a single variable.
Tuples are <b>ordered</b>, <b>immutable</b> (cannot be changed), and allow <b>duplicate values</b>.
</p>

<hr>

<h2> Creating Tuples</h2>

<pre>
numbers = (1, 2, 3, 4)
names = ("Python", "Java", "C")
single = (10,)      # single element tuple
</pre>

<hr>

<h2> Accessing Tuple Elements</h2>

<pre>
colors = ("red", "green", "blue")

print(colors[0])    # red
print(colors[-1])   # blue
</pre>

<hr>

<h2> Tuple Slicing</h2>

<pre>
nums = (10, 20, 30, 40, 50)

print(nums[1:4])    # (20, 30, 40)
</pre>

<hr>

<h2> Tuple Immutability</h2>
<p>
Tuples cannot be modified after creation.
</p>

<pre>
t = (1, 2, 3)
# t[0] = 10   ❌ This will cause an error
</pre>

<hr>

<h2> Tuple Methods</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Method</th>
    <th>Description</th>
    <th>Example</th>
</tr>

<tr>
    <td>count()</td>
    <td>Returns number of occurrences</td>
    <td>(1,2,2,3).count(2)</td>
</tr>

<tr>
    <td>index()</td>
    <td>Returns index of element</td>
    <td>(10,20,30).index(20)</td>
</tr>

</table>

<hr>

<h2> Tuple Built-in Functions</h2>

<ul>
    <li><b>len()</b> – Returns number of elements</li>
    <li><b>max()</b> – Returns maximum value</li>
    <li><b>min()</b> – Returns minimum value</li>
    <li><b>sum()</b> – Returns sum of elements</li>
    <li><b>type()</b> – Returns data type</li>
</ul>

<hr>

<h2> Converting Tuple to List</h2>

<pre>
t = (1, 2, 3)
lst = list(t)
print(lst)
</pre>

<hr>

<h2> Tuple Packing and Unpacking</h2>

<pre>
# Packing
t = 10, 20, 30

# Unpacking
a, b, c = t
print(a, b, c)
</pre>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1> Sets in Python</h1>
<hr>

<h2> What is a Set?</h2>
<p>
A <b>set</b> is a built-in data type in Python used to store multiple values in a single variable.
Sets are <b>unordered</b>, <b>mutable</b>, and do <b>not allow duplicate values</b>.
</p>

<hr>

<h2> Creating Sets</h2>

<pre>
numbers = {1, 2, 3, 4}
names = {"Python", "Java", "C"}
duplicates = {1, 2, 2, 3}
print(duplicates)   # {1, 2, 3}
</pre>

<hr>

<h2> Accessing Set Elements</h2>
<p>
Sets are unordered, so elements cannot be accessed using index.
Use a loop to access elements.
</p>

<pre>
fruits = {"apple", "banana", "cherry"}

for item in fruits:
    print(item)
</pre>

<hr>

<h2> Adding and Removing Elements</h2>

<pre>
s = {1, 2, 3}

s.add(4)
s.remove(2)
s.discard(5)   # no error if element not found
print(s)
</pre>

<hr>

<h2> Set Methods</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Method</th>
    <th>Description</th>
    <th>Example</th>
</tr>

<tr>
    <td>add()</td>
    <td>Adds element to set</td>
    <td>s.add(5)</td>
</tr>

<tr>
    <td>remove()</td>
    <td>Removes specified element</td>
    <td>s.remove(2)</td>
</tr>

<tr>
    <td>discard()</td>
    <td>Removes element without error</td>
    <td>s.discard(10)</td>
</tr>

<tr>
    <td>pop()</td>
    <td>Removes random element</td>
    <td>s.pop()</td>
</tr>

<tr>
    <td>clear()</td>
    <td>Removes all elements</td>
    <td>s.clear()</td>
</tr>

</table>

<hr>

<h2> Set Operations</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Operation</th>
    <th>Symbol</th>
    <th>Example</th>
</tr>

<tr>
    <td>Union</td>
    <td>|</td>
    <td>a | b</td>
</tr>

<tr>
    <td>Intersection</td>
    <td>&</td>
    <td>a & b</td>
</tr>

<tr>
    <td>Difference</td>
    <td>-</td>
    <td>a - b</td>
</tr>

<tr>
    <td>Symmetric Difference</td>
    <td>^</td>
    <td>a ^ b</td>
</tr>

</table>

<hr>

<h2> Example Program</h2>

<pre>
a = {1, 2, 3}
b = {3, 4, 5}

print("Union:", a | b)
print("Intersection:", a & b)
print("Difference:", a - b)
print("Symmetric Difference:", a ^ b)
</pre>

<hr>

<h2> Frozen Set</h2>
<p>
A <b>frozenset</b> is an immutable version of a set.
</p>

<pre>
fs = frozenset([1, 2, 3])
print(fs)
</pre>

<hr>

<h2> Built-in Functions with Sets</h2>

<ul>
    <li><b>len()</b> – Returns number of elements</li>
    <li><b>max()</b> – Returns maximum value</li>
    <li><b>min()</b> – Returns minimum value</li>
    <li><b>sum()</b> – Returns sum of elements</li>
    <li><b>type()</b> – Returns data type</li>
</ul>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1>Dictionaries in Python</h1>
<hr>

<h2> What is a Dictionary?</h2>
<p>
A <b>dictionary</b> is a built-in data type in Python used to store data in
<b>key–value pairs</b>.
Dictionaries are <b>unordered</b>, <b>mutable</b>, and keys must be <b>unique</b>.
</p>

<hr>

<h2> Creating a Dictionary</h2>

<pre>
student = {
    "name": "Rizwana",
    "age": 21,
    "course": "Python"
}
</pre>

<hr>

<h2> Accessing Dictionary Elements</h2>

<pre>
print(student["name"])
print(student.get("age"))
</pre>

<hr>

<h2> Modifying Dictionary</h2>

<pre>
student["age"] = 22
student["city"] = "Hyderabad"
print(student)
</pre>

<hr>

<h2> Removing Elements</h2>

<pre>
student.pop("city")
del student["course"]
print(student)
</pre>

<hr>

<h2> Dictionary Methods</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Method</th>
    <th>Description</th>
    <th>Example</th>
</tr>

<tr>
    <td>keys()</td>
    <td>Returns all keys</td>
    <td>dict.keys()</td>
</tr>

<tr>
    <td>values()</td>
    <td>Returns all values</td>
    <td>dict.values()</td>
</tr>

<tr>
    <td>items()</td>
    <td>Returns key-value pairs</td>
    <td>dict.items()</td>
</tr>

<tr>
    <td>get()</td>
    <td>Returns value of key</td>
    <td>dict.get("name")</td>
</tr>

<tr>
    <td>update()</td>
    <td>Updates dictionary</td>
    <td>dict.update({"age":25})</td>
</tr>

<tr>
    <td>pop()</td>
    <td>Removes specified key</td>
    <td>dict.pop("age")</td>
</tr>

<tr>
    <td>clear()</td>
    <td>Removes all items</td>
    <td>dict.clear()</td>
</tr>

<tr>
    <td>copy()</td>
    <td>Returns a copy</td>
    <td>dict.copy()</td>
</tr>

</table>

<hr>

<h2> Looping Through Dictionary</h2>

<pre>
for key, value in student.items():
    print(key, ":", value)
</pre>

<hr>

<h2> Built-in Functions with Dictionary</h2>

<ul>
    <li><b>len()</b> – Returns number of key-value pairs</li>
    <li><b>type()</b> – Returns data type</li>
</ul>

<hr>

<h2> Dictionary with Nested Data</h2>

<pre>
students = {
    "s1": {"name": "Asha", "marks": 90},
    "s2": {"name": "Ravi", "marks": 85}
}
</pre>

<hr>

<h2> Difference Between List and Dictionary</h2>

<table border="1" cellpadding="8">
<tr>
    <th>List</th>
    <th>Dictionary</th>
</tr>

<tr>
    <td>Stores values only</td>
    <td>Stores key-value pairs</td>
</tr>

<tr>
    <td>Accessed by index</td>
    <td>Accessed by key</td>
</tr>

<tr>
    <td>Ordered</td>
    <td>Unordered</td>
</tr>

</table>

<hr>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1>2️. Intermediate Python</h1>
<hr>

<p>
Intermediate Python concepts help you write <b>efficient</b>, <b>readable</b>,
and <b>professional</b> Python programs. These topics are essential before
moving to advanced Python.
</p>

<hr>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
</head>

<body>

<h1> python Looping Statements </h1>
<hr>

<h2> What is a Loop?</h2>
<p>
A <b>loop</b> is used to execute a block of code repeatedly
until a specific condition is satisfied.
Loops help reduce code repetition and improve efficiency.
</p>

<hr>

<h2> Types of Looping Statements in Python</h2>
<ul>
    <li>for loop</li>
    <li>while loop</li>
    <li>Nested loops</li>
</ul>

<hr>

<h2> 1. for Loop</h2>
<p>
The <b>for loop</b> is used to iterate over a sequence such as
a list, tuple, string, or range.
</p>

<pre>
for i in range(1, 6):
    print(i)
</pre>

<hr>

<h2> 2. while Loop</h2>
<p>
The <b>while loop</b> executes as long as the condition is true.
</p>

<pre>
i = 1
while i <= 5:
    print(i)
    i += 1
</pre>

<hr>

<h2> 3. Nested Loops</h2>
<p>
A <b>nested loop</b> is a loop inside another loop.
</p>

<pre>
for i in range(1, 4):
    for j in range(1, 4):
        print(i, j)
</pre>

<hr>

<h2>Loop Control Statements</h2>

<table border="1" cellpadding="8">
<tr>
    <th>Statement</th>
    <th>Description</th>
    <th>Example</th>
</tr>

<tr>
    <td>break</td>
    <td>Stops the loop immediately</td>
    <td>if i == 3: break</td>
</tr>

<tr>
    <td>continue</td>
    <td>Skips current iteration</td>
    <td>if i == 3: continue</td>
</tr>

<tr>
    <td>pass</td>
    <td>Does nothing (placeholder)</td>
    <td>pass</td>
</tr>

</table>

<hr>

<h2> Example Using break</h2>

<pre>
for i in range(1, 6):
    if i == 4:
        break
    print(i)
</pre>

<hr>

<h2> Example Using continue</h2>

<pre>
for i in range(1, 6):
    if i == 3:
        continue
    print(i)
</pre>

<hr>

<h2> Using else with Loops</h2>
<p>
The <b>else</b> block executes when the loop completes normally.
</p>

<pre>
for i in range(3):
    print(i)
else:
    print("Loop completed")
</pre>

<hr>

<h2> Infinite Loop Example</h2>
<p><b>Note:</b> Use carefully.</p>

<pre>
while True:
    print("Hello")
</pre>

<hr>

<h2> Advantages of Loops</h2>
<ul>
    <li>Reduces code repetition</li>
    <li>Improves readability</li>
    <li>Saves time and effort</li>
</ul>

<hr>





