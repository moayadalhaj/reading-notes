## Reading and Writing Files in Python

- You can read and writ files with Python. Whether it’s writing to a simple text file, reading a complicated server log, or even analyzing raw byte data, all of these situations require reading or writing a file.

- A file is a contiguous set of bytes used to store data. This data is organized in a specific format and can be anything as simple as a text file or as complicated as a program executable. In the end, these byte files are then translated into binary 1 and 0 for easier processing by the computer.

- Files contain of:

Header: metadata about the contents of the file (file name, size, type, and so on)

Data: contents of the file as written by the creator or editor

End of file (EOF): special character that indicates the end of the file

- What this data represents depends on the format specification used, which is typically represented by an extension.

- When you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file. It’s broken up into three major parts:

Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)

File Name: the actual name of the file

- You should always make sure that an open file is properly closed.

Characters Meaning
```
'r' =>	Open for reading (default)

'w' =>	Open for writing, truncating (overwriting) the file first

'rb' or 'wb' =>	Open in binary mode (read/write using byte data)
```

### There are three different categories of file objects:

- Text files

- Buffered binary files

- Raw binary files

## Python Exceptions: An Introduction

- A Python program terminates as soon as it encounters an error. In Python, an error can be a syntax error or an exception.

- Syntax errors occur when the parser detects an incorrect statement.

- Exception errors occur whenever syntactically correct Python code results in an error.

- The try and except block in Python is used to catch and handle exceptions. Python executes code following the try statement as a “normal” part of the program. The code that follows the except statement is the program’s response to any exceptions in the preceding try clause.

- when syntactically correct code runs into an error, Python will throw an exception error. This exception error will crash the program if it is unhandled. The except clause determines how your program responds to exceptions.


- `raise` allows you to throw an exception at any time.

- `assert` enables you to verify if a certain condition is met and throw an exception if it isn’t.

- In the `try` clause, all statements are executed until an exception is encountered.

- `except` is used to catch and handle the exception(s) that are encountered in the try clause.

- `else` lets you code sections that should run only when no exceptions are encountered in the try clause.

- `finally` enables you to execute sections of code that should always run, with or without any previously encountered exceptions.
