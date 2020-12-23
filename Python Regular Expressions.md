## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Regular Expressions
Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not. If you've ever used search engines, search and replace tools of word processors and text editors - you've already seen regular expressions in use. They are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc. They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.
## Regular Expressions in Python
In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import
Basic Patterns: Ordinary Characters
Ordinary characters are the simplest regular expressions. They match themselves exactly and do not have a special meaning in their regular expression syntax.
Examples
pattern = r"Cookie"
sequence = "Cookie"
if re.match(pattern, sequence):
    print("Match!")
else: print("Not a match!")
The match() function returns a match object if the text matches the pattern. Otherwise, it returns None
Do you notice the r at the start of the pattern Cookie?
This is called a raw string literal. It changes how the string literal is interpreted. Such literals are stored as they appear.


# shutil High-level File Operations
Shutil module in Python provides many functions of high-level operations on files and collections of files. It comes under Python’s standard utility modules. This module helps in automating process of copying and removal of files and directories.

shutil.copy() method in Python is used to copy the content of source file to destination file or directory. It also preserves the file’s permission mode but other metadata of the file like the file’s creation and modification times is not preserved.
