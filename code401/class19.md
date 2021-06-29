# Regular Expressions in Python
 In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import

 `import re`

 ## Basic Patterns: Ordinary Characters
 You can easily tackle many basic patterns in Python using ordinary characters. Ordinary characters are the simplest regular expressions. They match themselves exactly and do not have a special meaning in their regular expression syntax.

 Examples are 'A', 'a', 'X', '5'.

 ## Wild Card Characters: Special Characters
 Special characters are characters that do not match themselves as seen but have a special meaning when used in a regular expression. For simple understanding, they can be thought of as reserved metacharacters that denote something else and not what they look like.
 - . - A period. Matches any single character except the newline character.
 - ^ - A caret. Matches the start of the string.
 - $ - Matches the end of string.
 - [abc] - Matches a or b or c.
 - [a-zA-Z0-9] - Matches any letter from (a to z) or (A to Z) or (0 to 9).
 - \ - Backslash.
Perhaps, the most diverse metacharacter!!

If the character following the backslash is a recognized escape character, then the special meaning of the term is taken (Scenario 1)
Else if the character following the \ is not a recognized escape character, then the \ is treated like any other character and passed through (Scenario 2).
\ can be used in front of all the metacharacters to remove their special meaning (Scenario 3).

# shutil High-level File Operations
Shutil module in Python provides many functions of high-level operations on files and collections of files. It comes under Python’s standard utility modules. This module helps in automating process of copying and removal of files and directories.

shutil.copy() method in Python is used to copy the content of source file to destination file or directory. It also preserves the file’s permission mode but other metadata of the file like the file’s creation and modification times is not preserved.

## Automation
Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not. If you've ever used search engines, search and replace tools of word processors and text editors - you've already seen regular expressions in use. They are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc. They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.
In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import:


