[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15167772&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

  Answer
   Definition:
   Python is a high-level, interpreted programming language that is widely used for many different purposes, from web development to scientific computing to machine learning.

   key features:
   a) Easy to learn: Python has a relatively simple syntax, which makes it easier for beginners to learn compared to other programming languages.
   b) Versatile: Python can be used for a wide range of applications, including web development, data analysis, artificial intelligence, and more.
   c) Large and active community: There is a large and active community of Python developers, which means that there are many resources available for learning and solving problems.
   d) Plenty of libraries: Python has a large number of libraries which can be used to perform complex tasks with just a few lines of code.
   e) Cross-platform compatibility: Python can run on multiple operating systems.
    
   examples of use cases:
   a) Web Development: Frameworks like Django and Flask.
   b) Data Science: Libraries like Pandas, NumPy, and Matplotlib.
   c) Machine Learning: Libraries like TensorFlow and Scikit-learn.
   d) Automation: Scripting and task automation.
   e) Software Development: Building applications with Tkinter or PyQt.
   f) Network Programming: Libraries like socket and asyncio.



2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Answers:
   Download the Installer:
   a) Go to the official Python website (python.org) and download the Windows installer.
   
   Run the Installer:
   b) Run the downloaded installer and make sure to check the box that says "Add Python to PATH".
   c) Follow the installation steps.
   
   Verify the Installation:
   d) Open Command Prompt and type 'python --version' or 'python -V'.

   Setting up a virtuan environment:
   First install the virtual environment by accessing the cmd and running as administrator then run ; 
     pip install virtualenv

   Then open the powershell and run the command ;
     virtualenv Project
     cd Project
     Scripts/activate



3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.


Answers:
    print("Hello, World!")

    <!-- print: This is a built-in function that outputs text to the console.
    "Hello, World!": This is a string, a sequence of characters enclosed in quotation marks. -->



4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Answers:

   Integer (int): Whole numbers, e.g., 42.
   Float (float): Decimal numbers, e.g., 3.14.
   String (str): Sequence of characters, e.g., "Hello".
   Boolean (bool): Represents True or False.
   List (list): Ordered, mutable collection of items, e.g., [1, 2, 3].
   Dictionary (dict): Unordered collection of key-value pairs, e.g., {"name": "Alice", "age": 30}.

   script code:

   # Integer
     age = 25
     print(f"Age: {age}")

   # Float
     height = 5.9
     print(f"Height: {height}")

   # String
     name = "John Doe"
     print(f"Name: {name}")

   # Boolean
     is_student = True
     print(f"Is Student: {is_student}")

   # List
     numbers = [1, 2, 3, 4, 5]
     print(f"Numbers: {numbers}")

   # Dictionary
     person = {"name": "Alice", "age": 30}
     print(f"Person: {person}")



5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.


    Answers:

    conditional statements using if-else statements

    # if else example
    age = 18

    if age >= 18:
       print("You are an adult.")
    else:
       print("You are a minor.")


    For loop statements

    # For loop example
    for i in range(5):
       print(f"Iteration {i}")



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Answers:

   Functions are reusable blocks of code that perform specific tasks. They take inputs, process them, and return outputs.

   Why they are useful:

   a) Reusability: Write once, use multiple times.
   b) Modularity: Break complex problems into smaller parts.
   c) Readability: Make code easier to understand.
   d) Maintainability: Simplify debugging and testing.
   e) bstraction: Hide implementation details.


   # Function definition
     def add_numbers(x, y):
        return x + y

   # Calling the function
     result = add_numbers(9, 3)
     print("The sum is:", result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.


Answers:

   Differences between lists and dictionaries:

   Lists: Ordered collections that allow duplicate elements.
   Dictionaries: Unordered collections that store key-value pairs with unique keys.

  # List example
     numbers = [1, 2, 3, 4, 5]
     print("Numbers:", numbers)

  # Dictionary example
     person = {"name": "Alice", "age": 30}
     print("Person:", person)

  # List operations
     numbers.append(6)
     print("Updated Numbers:", numbers)

  # Dictionary operations
     person["city"] = "New York"
     print("Updated Person:", person)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Answers:

   Exception handling is a mechanism to manage errors during program execution, ensuring the program can handle unexpected situations gracefully.

   code example:
   
   try:
     # Code that might raise an exception
    result = 10 / 0
   except ZeroDivisionError:
     # Code to handle the exception
    print("Cannot divide by zero.")
   finally:
     # Code that runs no matter what
    print("Execution completed.")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Answers:

   Modules: Files containing Python code.
   Packages: Directories containing multiple modules.

   Using Math module:

   import math

    # Using a function from the math module

     result = math.sqrt(16)
     print("The square root of 16 is:", result)



10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   Answers:

   # Reading from a file
   with open('example.txt', 'r') as file:
      content = file.read()
      print(content)


    # Writing to a file
   lines = ["Hello, World!", "Python is great!", "File I/O is easy."]

   with open('output.txt', 'w') as file:
      for line in lines:
          file.write(line + "\n")


 CITATIONS
  LMS notes.
  W3 Schools.


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


