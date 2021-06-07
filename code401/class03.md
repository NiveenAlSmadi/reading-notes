# FileIO & Exceptions
## Reading and Writing Files in Python 

### What Is a File?
Files on most modern file systems are composed of three main parts:

- Header: metadata about the contents of the file (file name, size, type, and so on)
- Data: contents of the file as written by the creator or editor
- End of file (EOF): special character that indicates the end of the file

`File Paths` :
- Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)

- File Name: the actual name of the file

- Extension: the end of the file path pre-pended with a period (.) used to indicate the file type

### Opening and Closing a File in Python
1- to open file in python  `file = open('dog_breeds.txt')`

2- 'r'	Open for reading (default)

3- 'w'	Open for writing, truncating (overwriting) the file first

4-'rb' or 'wb'	Open in binary mode (read/write using byte data)


### There are three different categories of file objects:

1-Text files

2-Buffered binary files

3-Raw binary files
## Working With Bytes
Sometimes, you may need to work with files using byte strings. This is done by adding the 'b' character to the mode argument 
## Tips and Tricks
Now that you’ve mastered the basics of reading and writing files, here are some tips and tricks to help you grow your skills.

`__file__`
The `__file__ `attribute is a special attribute of modules, similar to `__name__`. 


------------------------------------------------------
## Python Exceptions
- Exceptions versus Syntax Errors
Syntax errors occur when the parser detects an incorrect statement.

- exception error This type of error occurs whenever syntactically correct Python code results in an error. 

## Raising an Exception
We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.


![img](https://files.realpython.com/media/raise.3931e8819e08.png)


## The AssertionError Exception
Instead of waiting for a program to crash midway, we  can also start by making an assertion in Python. 
![img](https://files.realpython.com/media/assert.f6d344f0c0b4.png)


so :
- raise allows you to throw an exception at any time.
- assert enables you to verify if a certain condition - is met and throw an exception if it isn’t.
- In the try clause, all statements are executed until an exception is encountered.
- except is used to catch and handle the exception(s) that are encountered in the try clause.
- else lets you code sections that should run only when no exceptions are encountered in the try clause.

