#0x0C-python-almost_a_circle 
This Project was done during **Full Stack Software Engineering studies @ alx africa and holberton school**
It aims was to learn about:-
 - What is Unit testing and how to implement it in a large project
How to serialize and deserialize a Class.
 - How to serialize and deserialize a Class.
 - How to write and read a JSON file- What is `*args` and how to use it.
 - What is `**kwargs` and how to use it.
 - How to handle named arguments in a function.

Background Context
   -----------------
The AirBnB project is a big part of the Higher level curriculum. This project will help you be ready for it.
In this project, you will review everything about Python:
- import
- Exceptions
- Class
- Private attribute
- Getter/Setter
- Class method
- Static method
- Inheritance
- Unittest
- Read/Write file

You will also learn about:
- `args` and `kwargs`
- Serialization/Deserialization
- JSON

# Requirements
Python Scripts
  --------------------
 - Allowed editors: `vi, vim, emacs`
 - Scripts written in Bash `5.0.17(1)`
 - All Python files are intepreted using `Python3 (3.8.5)`
 - All scripts were Tested on Ubuntu `20.04 LTS`
 - All codes were tested on `pycodestyle (version 2.8.*)`
 - All your files must be executable.
 - The length of your files will be tested using `wc`
- All your test files should be text files ` (extension: .txt)`          
- All your tests should be executed by using this command: `python3 -m doctest ./tests/*`                     
- All your modules should have a documentation `(python3 -c 'print(__import__("my_module").__doc__)')`        
- All your classes should have a documentation `(python3 -c 'print(__impo
rt__("my_module").MyClass.__doc__)')
- All your functions (inside and outside a class) should have a documentation `(python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')`
 - A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
 - We strongly encourage you to work together on test cases, so that you don’t miss any edge case

Python Unit Tests
  ------------------
- Allowed editors: `vi, vim, emacs`
- All your files should end with a new line.
- All your test files should be inside a folder `tests`
- You have to use the `unittest module`
- All your test files should be python files (extension:`.py`)
- All your test files and folders should start with test_
- Your file organization in the tests folder should be the same as your project: ex: for `models/base.py`, unit tests must be in: `tests/test_models/test_base.py`
- All your tests should be executed by using this command:`python3 -m unittest discover tests`
- You can also test file by file, by using this command: `python3 -m unittest tests/test_models/test_base.py`
- We strongly encourage you to work together on test cases so that you don't miss any edge case.

Files
   -------------

The following files are scripts and programs written in Python

| Filename | Description |
| ----- | ------- |
| `tests/` |  All your files, classes and methods must be unit tested and be PEP 8 validated.|
| `models/base.py, models/__init__.py` | Write the first class `Base`: This class will be the "base" of all other classes in this project. The goal of it is to manage `id` attribute in all your future classes and to avoid duplicating the same code (by extension, same bugs) | 
| `models/rectangle.py` | Write the class `Rectangle` that inherits from `Base`: Why private attributes with getter/setter? Why not directly public attribute? Because we want to protect attributes of our class. With a setter, you are able to validate what a developer is trying to assign to a variable. So after, in your class you can "trust" these attributes. |
| `models/square.py` | Write the class `Square` that inherits from `Rectangle` |
| |
 
