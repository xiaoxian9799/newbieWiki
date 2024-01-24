# Automate the Boring Stuff with Python
Reference: https://automatetheboringstuff.com/

## Table of Contents   
**Part I: Python Programming Basics**        
- [X] <!-- 20240117 -->[Introduction](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#introduction)      
- [X] <!-- 20240117 -->[01 - Python Basics](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#01---python-basics)      
- [X] <!-- 20240117 -->[02 - Flow Control](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#02---flow-control)      
- [X] <!-- 20240117 -->[03 - Functions](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#03---functions)      
- [X] <!-- 20240118 -->[04 - Lists](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#04---lists)      
- [X] <!-- 20240118 -->[05 - Dictionaries and Structuring Data](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#04---lists)    
- [X] <!-- 20240118 -->[06 - Manipulating Strings](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#06---manipulating-strings)

**Part II: Automating Tasks**    
- [X] <!-- 20240119 -->[07 - Pattern Matching with RegEx](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#07---pattern-matching-with-regex)    
- [X] <!-- 20240119 -->[08 - Input Validation](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#08---input-validation)    
- [X] <!-- 20240122 -->[09 - Reading and Writing Files](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#09---reading-and-writing-files)
- [X] <!-- 20240122 -->[10 - Organizing Files](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#10---organizing-files)
- [X] <!-- 20240122 -->[11 - Debugging](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#11---debugging)
- [X] <!-- 20240122 -->[12 - Web Scraping](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#12---web-scraping)
- [X] <!-- 20240122 -->[13 - Working with Excel Spreadsheets](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#13---working-with-excel-spreadsheets)
- [X] <!-- 20240124 -->[14 - Working with Google Spreadsheets](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#14---working-with-google-spreadsheets)
- [X] <!-- 20240124 -->[15 - Working with PDF and Word Documents](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#15---working-with-pdf-and-word-documents)
- [ ] [16 - Working with CSV Files and JSON Data](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#15---working-with-pdf-and-word-documents)
- [ ] [17 - Keeping Time, Scheduling Tasks, and Launching Programs](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#17---keeping-time-scheduling-tasks-and-launching-programs)
- [ ] [18 - Sending Email and Text Messages](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#18---sending-email-and-text-messages)
- [ ] [19 - Manipulating Images](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#19---manipulating-images)
- [ ] [20 - Controlling the Keyboard and Mouse with GUI Automation](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#20---controlling-the-keyboard-and-mouse-with-gui-automation)

## Introduction 
- Examples of _operating system_: Microsoft Windows, Linux OS, Apple macOS, Apple iOS, Google's Android OS   
- The _interactive shell_ is good for _running or executing_ Python _instructions_ one at a time (by using >>> _prompt_), whereas _file editor_ is good to write instructions for the entire Python programs.
- Both _compiler_ and _interpreter_ translate _source code_ (that adhere to _syntax rules_) into machine code. Compiler translates code at once before the program runs, whereas interpreter translates code line-by-line as the program runs.    
- Writing programs involves breaking down a problem into individual, detailed steps.     
    
_built-in functions_    
_standard library_   
A _module_ is a Python program that contains a related group of functions that can be embedded in your programs.    

```Python
  import module_name, ...
  module_name.func_name()

  from module_name import *
  func_name()
```

## 01 - Python Basics
- _Expressions_ are formed by putting _values_ and _operators_ together, and they always _evaluate_ down to a single value.    
- A _data type_ is a category for values, examples: _int_, _float_, _str_, and _Boolean_.
- A _variable_ is _initialized or created_ the first time a value is stored in it. The variable can be _overwritten_ when it is assigned a new value.
  
- The Python program _terminates or exits_ when there are no more lines of code to execute. CTRL-C is handy if you want to simply terminate your program immediately or when your program is stuck in an infinite loop. The Python program _crash_ (the program stopped running unexpectedly) if they contain code the computer can't understand, which will cause Python to show an error message.
  
- Python is _calling_ the `print() ` function and the _argument_ (i.e. string value) is being _passed_ to the function.
- The `input()` function waits for the user to type some text on the keyboard and press ENTER.
- The `len()` function evaluates to the integer value of the number of characters in a string.
  
- The `str()`, `int()`, and `float()` functions evaluate to the string, integer, and floating-point forms of the value you pass, respectively.
- An integer can be equal to a floating point. Example: `42 == 42.0`    

`SyntaxError: EOL while scanning string literal` means you probably forgot the final single quote character at the end of the string.

| Operators | Math Operations | String Operations |
| :---: | --- | --- |
| + | Addition | String concatenation |
| * | Multiplication | String replication |

_assignment statement_ `var_name = val`    
_assignment operator_ `=`

### Naming Rules for Variable
- Only one word with no spaces.
- Only letters, numbers, and `_` char.
- Cannot begin with a number.

- case-sensitive    

_comment_ `#`   

## 02 - Flow Control
flowchart    

Comparison operators or relational operators

| Boolean Operators | |
| --- | --- |
| `and` | Binary |
| `or` | Binary |
| `not` | Unary |

> [!NOTE]
> Precedence
> `not` > `and` > `or`

Truth table    

clause

- _Conditions_ are the same thing as expressions; condition is just a more specific name in the context of flow control statements. Conditions always evaluate down to a _Boolean value_, `True` or `False`.

Blocks begin when the indentation increases.

Flow control statements: `if`, `else`, `elif`, `while` loop, `break`, `continue`, `for` loop, 

> [!NOTE]
> The order of the `elif` statements does matter; the rest of the `elif` clauses are automatically skipped once a `True` condition has been found.

```Python
if condition:
  clause
elif condition:
  clause
else:
  clause
```

```Python
while condition:
  clause
  if condition:
    continue    # jump back to the loop's start
  if condition:
    break    # exit a loop
```

```Python
for var_name in range(start_arg, stop_arg, step_arg):
  clause
  if condition:
    continue
  if condition:
    break
```

iteration    

```Python
import sys

sys.exit()    # terminate or exit the program before the last instruction
```

## 03 - Functions 
to _deduplicate_ code (getting rid of duplicated or copy-and-pasted code) to make your program shorter, easier to read, and easier to update.    

```Python
def func_name(optional_parameter_name):    # define or create a function
  func_body
  return return_val

var_name = func_name(keyword_arg_value)    # function call
```

- _Parameters_ are variables that contain _arguments_. A value being passed to a function in a function call is an argument.
- When a function is called with arguments, the arguments are stored in the parameters. The value stored in a parameter is forgotten when the function returns.

`None` is called as `null`, `nil`, or `undefined` in other programming languages.    

When your program calls a function, Python creates a _frame object_ on the top of the _call stack_. Frame objects store the line number of the original function call so that Python can remember where to return.

Parameters and variables that are assigned in a called function are said to be exist in that function's _local scope_. Variables that are assigned outside all functions are said to exist in the _global scope_. A variable must be one or the other; it cannot be both local and global.

### Exception Handling
The entire program will crash when you get an error, or _exception_ in your Python program.    
Errors can be handled with `try` and `except` statements.     
- The code that could potentially have an error is put in a `try` clause.
- The program execution moves to the start of a following `except` clause if an error happens.

## 04 - Lists  &  05 - Dictionaries and Structuring Data 

| | Strings | Lists | Tuples | Dictionaries |
| --- | --- | --- | --- | --- |
| Items Sequence | | ordered | ordered | unordered |
| | ' ' or " " | [ ] | ( ) | { } |
| Items | | _comma-delimited_ | _comma-delimited_ | _comma-delimited_ |
| `len()` | num of chars | num of vals | |
| Concatenation with `+` or `+=` | / | / | |
| Replication with `*` or `*=` | / | / | |
| **Data Type** | _immutable_ | _mutable_ | _immutable_ | _mutable_ |
| Conversion | str() | list() | tuple() |

Mutable data type means it can have values added, removed, or changed.    
The proper way to "mutate" a string is to use slicing and concatenation to build a new string by copying from parts of the old string.

Example:
```Python
>>> name = 'newbieWiki'
>>> newName = name[0:6] + 'Help'
>>> name
'newbieWiki'
>>> newName
'newbieHelp'
```

```Python
>>> ls_name = [['a', 'b', 'c'], [10, 20, 30]]

>>> ls_name[0]  
['a', 'b', 'c']

>>> ls_name[1][2]
30

>>> ls_name = ['a', 'b', 'c']

>>> ls_name[-1]       # ls_name[index] 
'c'

>>> ls_name[1:2]      # ls_name[slice_starts:slice_ends] 
'b'

>>> del ls_name[2]    # removes a value from the list (using index), return None [vs ls_name.remove(val)]
>>> ls_name
['a', 'b']

>>> 'a' in ls_name
True

>>> 'a' not in ls_name
False
```

### The Multiple Assignment Trick
aka _tuple unpacking_

```Python
cat = ['fat', 'gray', 5]
size, color, age = cat

>>> color
gray
```

```Python
# enumerate() returns two values: the index of the item in the list, and the item in the list itself
>>> fruits = ['avocado', 'banana', 'honeydew']
>>> for index, fruit in enumerate(fruits):
...    print('Index ' + str(index) + 'in fruits is: ' + fruit)

Index 0 in fruits is: avocado
.
.
.

import random
random.choice(ls_name)     # returns a randomly selected item from the list
random.shuffle(ls_name)    # reorders the items in a list, returns None
```

| Augmented Assignment Operator |
| :---: |
| += |
| -= |
| *= |
| /= |
| %= |

### Methods
Each data type has its own set of methods.

```Python
>>> ls_name.index(val)            # returns the index of the value, if that value exists in the list
>>> ls_name.append(val)           # adds a value to the end of the list, returns None
>>> ls_name.insert(index, val)    # adds a value at any index in the list, returns None
>>> ls_name.remove(val)           # removes a value from the list (using value), returns None [vs del ls_name(index)]
>>> ls_name.sort()                # sorts the list of number values or list of string, uses “ASCIIbetical order”, returns None
>>> ls_name.sort(reverse=True)    # sorts the list of number values or list of string, in reverse order, returns None
>>> ls_name.sort(key=str.lower)   # sorts the list of number values or list of string, uses regular alphabetical order, returns None
>>> ls_name.reverse()             # reverses the order of the items in a list
```

> [!TIP]
> You can split up a single instruction across multiple lines using the `\` _line continuation character_ at the end.

```Python
>>> import copy
>>> ls_first = ['a', 'b', 'c']
>>> id(ls_first)    # obtain its unique identity
44684232
>>> ls_second = copy.copy(ls_first)
>>> id(ls_second)
44685832
```

If the list you need to copy contains lists, then use the `copy.deepcopy()` function instead of `copy.copy()`. The `deepcopy()` function will copy these inner lists as well.

### Dictionaries

```Python
>>> cat = {'size': 'fat', 'color': 'gray', 'age': 5}    # dict_name = {key:val, ...}
>>> cat['size']                                         # dict_name[key]
'fat'
```

```Python
>>> cat = {'size': 'fat', 'color': 'gray', 'age': 5}

>>> for k in cat.keys():      # dict_name.keys() returns keys
...  print(k)

size
color
age

>>> for v in cat.values():    # dict_name.values() returns values
...  print(v)

fat
gray
5

>>> for i in cat.items():     # dict_name.items() returns key-value pairs
...  print(i)

('size', 'fat')               # tuple
('color', 'gray')
('age', 5)

>>> for k, v in cat.items():
...  print(k + ': ' + str(v))

size: fat
color: gray
age: 5
```

```Python
val in dict_name.keys()      # check whether a certain key exists in a dictionary, returns Boolean
val in dict_name.values()    # check whether a certain value exists in a dictionary, returns Boolean

# get() method takes two arguments: the key of the value to retrieve and a fallback value to return if that key does not exist.
>>> 'The cat is ' + str(cat.get('size', 'small')) + '.'
'The cat is fat.'
>>> 'The cat is ' + str(cat.get('attr', 'cute')) + '.'
'The cat is cute.'

# setdefault() method takes two arguments: the key to check for and the value to set at that key if the key does not exist. If the key does exist, the setdefault() method returns the key's value.
>>> dict_name.setdefault(k_val, v_val)

import pprint                # pretty printing
pprint.pprint(dict_name)
pprint.pformat(dict_name)
```

## 06 - Manipulating Strings 
### Escape Characters
`\'`, `\"`, `\t`, `\n`, `\\`

### Raw Strings
A _raw string_ completely ignores all escape characters and prints any backslash that appears in the string.

```Python
>>> print(r' ')
```

### Multiline Strings
A multiline string in Python begins and ends with either three single quotes or three double quotes. Any quotes, tabs, or newlines in between the "triple quotes" are considered part of the string.

```Python
print('''


''')
```

### Multiline Comments
```Python
"""

"""
```

### String Interpolation
```Python
>>> name = 'xx'
>>> age = 99

>>> 'My name is %s. I am %s years old.' % (name, age)
'My name is xx. I am 99 years old.'

>>> f'My name is {name}. I am {age} years old.'
'My name is xx. I am 99 years old.'
```

```Python
# Methods to make a case-insensitive comparison
str_name = str_name.upper()    # returns a new string where all the letters in the original string have been converted to uppercase
str_name = str_name.lower()    # returns a new string where all the letters in the original string have been converted to lowercase
str_name.isupper()             # returns a Boolean True value if the string has at least one letter and all the letters are uppercase
str_name.islower()             # returns a Boolean True value if the string has at least one letter and all the letters are lowercase

# Methods to validate the user input
str_name.isalpha()             # returns a Boolean True value if the string consists only of letters and is not blank
str_name.isalnum()             # returns a Boolean True value if the string consists only of letters and numbers and is not blank
str_name.isdecimal()           # returns a Boolean True value if the string consists only of numeric characters and is not blank
str_name.isspace()             # returns a Boolean True value if the string consists only of spaces, tabs, and newlines and is not blank
str_name.istitle()             # returns a Boolean True value if the string consists only of words that begin with an uppercase letter followed by only lowercase letters

>>> 'hello'.isalnum()
True
>>> '    '.isspace()
True
>>> 'This Is Title Case'.istitle()
True
>>> 'This Is Title Case 123'.istitle()
True
>>> 'This Is not Title Case'.istitle()
False
>>> 'This Is NOT Title Case'.istitle()
False

str_name.startswith(str_val)    # returns a Boolean True value if the string begins with the string passed to the method
str_name.endswith(str_val)      # returns a Boolean True value if the string ends with the string passed to the method

>>> 'ABC'.join(['My', 'name', 'is', 'Simon'])
'MyABCnameABCisABCSimon'
>>> 'MyABCnameABCisABCSimon'.split('ABC')    # by default, the string is split whenever whitespace characters (space, tab, or newline characters) are found
['My', 'name', 'is', 'Simon']

# A common use of split() is to split a multiline strng along the \n newline characters.

# partition() method is useful for splitting a string whenever you need the parts before, including, and after a particular separator string.
>>> before, sep, after = 'xx@github.com'.partition('@')
>>> before
'xx'
>>> after
'github.com'

# If the separator string you pass to partition() occurs multiple times in the string that partition() calls on, the method splits the string only on the first occurrence:
>>> 'MyABCnameABCisABCSimon'.partition('ABC')
('My', 'ABC', 'nameABCisABCSimon')

# If the separator string can't be found, the first string returned in the tuple will be the entire string, and the other two strings will be empty:
>>> 'MyABCnameABCisABCSimon'.partition('banana')
('MyABCnameABCisABCSimon', '', '')
```

### Justifying Text
To print tabular data that has correct spacing (strings are neatly aligned).
`rjust(), ljust(), center()`

### Removing Whitespace
To strip off whitespace characters (space, tab, and newline)
`strip(), rstrip(), lstrip()`

### Copying and Pasting Strings
```Python
import pyperclip
pyperclip.copy(str_name)    # sends text to your computer's clipboard
pyperclip.paste()           # receives text from your computer's clipboard
```

## 07 - Pattern Matching with RegExes  
_Regular expressions_ allow you to specify a pattern of text to search for.

| Shorthand Char Class | Represents | Shorthand Char Class | Represents | 
| :---: | --- | :---: | --- |
| `\d` | Any numeric digit from 0 to 9 | `\D` | opposite of `\d` |
| `\w` | Any letter, numeric digit, or the underscore char | `\W` | opposite of `\w` |
| `\s` | Any space, tab, or newline char | `\S` | opposite of `\s` |
| [ ] | self-defined char class | [^ ] | self-defined negative char class (matches all the chars that are not in the char class|

Example:
`[aeiouAEIOU]` - matches any vowel, both lowercase and uppercase
`[a-zA-Z0-9]` - matches all lowercase letters, uppercase letters, and numbers
`[0-5\.]` - matches digits 0 to 5 and a period

```Python
>>> import re

# passing a string value representing your regular expression to re.compile() returns a Regex pattern object or Regex object
>>> phoneNumRegex = re.compile(r'\d\d\d-\d\d\d\d\d\d\d\d')    # the phoneNumRegex var contains a Regex object

# search() method searches the string it is passed for any matches to the regex, returns None if the regex pattern is not found in the string, and if the pattern is found, returns a Match object (mo), which has a group() method that will return the actual matched text from the searched string
>>> mo = phoneNumRegex.search('My number is 011-12345678.')
>>> print('Phone number found: ' + mo.group())
Phone number found: 011-12345678

# grouping with parentheses
>>> phoneNumRegex = re.compile(r'(\(\d\d\d\))-(\d\d\d\d\d\d\d\d)')    # escaping . ^ $ * + ? { } [ ] \ | ( ) char with a backslash 
>>> mo = phoneNumRegex.search('My number is (011)-12345678.')

>>> mo.group(0)    # or mo.group()
'(011)-12345678'
>>> mo.group(1)
'(011)'
>>> mo.group(2)
'12345678'

>>> mo.groups()
('(011)', '12345678')
>>> areaCode, mainNum = mo.groups()
>>> print(areaCode)
(011)
```

### Matching with |
```Python
# The | pipe char matches either one of the expressions. If both expressions occur in the searched string, the first occurence of matching text will be returned as mo.
>>> fruitRegex = re.compile(r'avocado|banana')
>>> mo = fruitRegex.search('banana and avocado)
>>> mo.group()
'banana'

>>> fruitRegex = re.compile(r'ba(nana|mama|sasa)')
>>> mo = fruitRegex.search('Hi bamama!')
>>> mo.group()
'bamama'
>>> mo.group(1)
'mama'
```

### Matching with ? * +
```Python
# The ? question mark char matches zero or one of the preceding group
>>> genderRegex = re.compile(r'(pine)?apple')
>>> mo = genderRegex.search('apple')
>>> mo.group()
'apple'
>>> mo = genderRegex.search('pineapple')
>>> mo.group()
'pineapple'

# The * star or asterisk char matches zero or more of the preceding group
>>> genderRegex = re.compile(r'(pine)*apple')
>>> mo = genderRegex.search('apple')
>>> mo.group()
'apple'
>>> mo = genderRegex.search('pineapple')
>>> mo.group()
'pineapple'
>>> mo = genderRegex.search('pinepineapple')
>>> mo.group()
'pinepineapple'

# The + plus char matches one or more of the preceding group
>>> genderRegex = re.compile(r'(pine)+apple')
>>> mo = genderRegex.search('apple')
>>> mo == None
True
>>> mo = genderRegex.search('pineapple')
>>> mo.group()
'pineapple'
>>> mo = genderRegex.search('pinepineapple')
>>> mo.group()
'pinepineapple'
```

### Matching with {n,m}
```Python
# The {n} matches exactly n of the preceding group
# The {n,} matches n or more of the preceding group
# The {,m} matches 0 to m of the preceding group
The {n,m} matches at least n and at most m of the preceding group
(group){n,m}
```

### Greedy and Non-greedy Matching
Python's regexes are _greedy_ by default, which means that in ambiguous situations they will match the longest string possible.     
The _non-greedy or lazy_ version of the braces, which matches the shortest string possible, has the closing brace followed by a ? question mark.
```Python
{n,m}?
*?
+?
```

```Python
# search() method returns a mo of the first matched text in the searched string, whereas the findall() method returns the strings of every match in the searched string

>>> fruitRegex = re.compile(r'\d\d-\d\d')        # has no groups
>>> fruitRegex.findall('01-23 45-67')
['01-23', '45-67']

>>> fruitRegex = re.compile(r'(\d\d)-(\d\d)')    # has groups
>>> fruitRegex.findall('01-23 45-67')
[('01', '23'), ('45', '67')]
```

### Matching with ^ $
```Python
# The ^ caret symbol at the start of a regex indicates that a match must occur at the beginning of the searched text.
# The $ dollar sign at the end of a regex indicates that a match must end with the regex pattern.
# The ^ and $ used together indicates that the entire string must match the regex.
```

### The Wildcard Char
The . dot char in a regex is called a _wildcard_ and will match any single char exceptthe newline.

### Matching with .*
The .* dot-star matches everything and anything (except a newline), in a greedy mode.    
The .*? dot-star-ques_mark matches everything and anything (except a newline), in a non-greedy fashion.    

### Matching Newlines with .*
```Python
>>>myRegex = re.compile('.*', re.DOTALL)
```

```Python
re.compile(,re.I)    # or re.IGNORECASE to make your regex case-insensitive
```

```Python
myRegex.sub('str_to_replace_any_matches', 'str_for_regex')

>>> secretRegex = re.compile(r'Agent \w+')
>>> secretRegex.sub('CENSORED', 'Agent Alice said hi to Agent Carol.')
'CENSORED said hi to CENSORED.'

>>> secretRegex = re.compile(r'Agent (\w)\w*')
>>> secretRegex.sub(r'\1****', 'Agent Alice said hi to Agent Carol.')
'A**** said hi to C****.'
```

```Python
# re.compile() function ignores whitespace and comments inside the regex string
myRegex = re.compile(r'''(
  (\d)?    # comment_1st
  (\s)     # comment_2nd
  )''', re.VERBOSE)
```

```Python
>>> myRegex = re.compile('my_str', re.IGNORECASE | re.DOTALL | re.VERBOSE)
```

## 08 - Input Validation    
### The PyInputPlus module
`pip install --user pyinputplus`    
`import pyinputplus as pyip`    

**Keyword Arguments**
- _min_, _max_, _greaterThan_, and _lessThan_
- _blank_
- _limit_, _timeout_, and _default_
- _allowRegexes_ and _blockRegexes_

- inputCustom()
    
## 09 - Reading and Writing Files

Filename    
Path    
File's extension = file's type    
Folders or directories (folder is the more modern name for directory)    

Root folder    
Volumes = ex. DVD drive or USB flash drive    

Current working directory or cwd    
Home directory or home folder    

Absolute path: always begins with the root folder    
Relative path: relative to the program's cwd        
. dot: shorthand for "this directory"    
.. dot-dot: shorthand for "the parent folder"    

| OS | Windows | macOS | Linux |
| --- | :---: | :---: | :---: |
| Path Separator | \ | / | / |

Path concatenation = `/`

```Python
>>> from pathlib import Path
# Path() will return a string with a file path using the correct path separators

>>> import os
>>> Path.cwd()              # get cwd
>>> os.chdir(p)        # change cwd

>>> os.makedirs(p)     # create new folders or directories
# os.makedirs() will create any necessary intermediate folders in order to ensure that the full path exists
>>> Path(p).mkdir()    # make a directory from a Path object
```

| C:\Users\folder\file.ext | | |
| --- | --- | --- |
| C: | Drive | storage device |
| C:\ | Anchor | root folder of the filesystem |
| \Users\folder\ | Parent | folder that contains the file |
| file.ext | Name |
| file | Stem or base name |
| ext | Suffix or extension |

| | |
| --- | --- |
| os.listdir(p) | returns a list of filename strings for each file in the path argument |
| p.glob(' ') | returns a list of filename strings for each file according to a _glob pattern_ (regex) |
| p.exists() | returns True if the path exists |
| p.is_file() | returns True if the path exists and is a file |
| p.is_dir() | returns True if the path exists and is a directory |

Plaintext files: text files (.txt), Python script files (.py)    
Binary files: All file types other than plaintext files: word processing docs, PDFs, images, spreadsheets, and executable programs

```Python
>>> file_obj = open(p, 'r')    # read mode
>>> file_content = file_obj.read()
>>> file_content = file_obj.readlines()

>>> file_obj = open(p, 'w')    # write mode: overwrites the exisiting file and starts from scratch, if the filename does not exist, creates a new, blank file
>>> file_obj = open(p, 'a')    # append mode: appends text to the end of the existing file, if the filename does not exist, creates a new, blank file
>>> file_obj.write('')

>>> file_obj.close()
```

Saving variables with 
- _shelve_ module
- pprint.pformat() function
  
## 10 - Organizing Files

| `shutil` or shell utilities | copy, move, rename, and delete files or folders |
| --- | --- |
| copy a file | `shutil.copy(source, destination)` |
| copy an entire folder and every folder and file contained in it | `shutil.copytree(source, destination)` |
| move or rename a file or folder | `shutil.move(source, destination)` |
| delete a folder and all of its contents | `shutil.rmtree(path)` |
| delete a file | `os.unlink(path)` |
| delete a folder (provided that the folder must be empty) | `os.rmdir(path)` |

`send2trash.send2trash()` function deletes files and folders by sending them to your computer's trash or recycle bin instead of permanently deleting them.    
`os.walk()` returns lists of strings (foldername, subfolders, and filenames)

archive file    

- Reading ZIP files `zipfile.ZipFile()`
- Extracting (opening) from ZIP files `extractall()` or `extract()`
- Creating and Adding to ZIP files `zipfile.ZipFile( , 'w')` or `zipfile.ZipFile( , 'a')`

## 11 - Debugging

### Raising Exceptions
Python raises an _exception_ whenever it tries to execute invalid code.

```Python
if condition:
  raise Exception('helpful_error_message')

try:
  ...
except Exception as err:
  ...
```

When Python encounters an error, it produces a treasure trove of error information called _traceback_.    
The traceback includes the error message, the line number of the line that caused the error, and the sequence of the function calls that led to the error.    
This sequence of calls is called the _call stack_.    

An _assertion_ is a sanity check to make sure your code isn't doing something obviously wrong. If an assert fails, your program should crash.    
Assertions are for programmer errors, not user errors.
```Python
assert condition, 'helpful_error_message'
```

`logging` module displays log messages in your screen as your program runs. Log messages are intended for programmers, not the users.

Logging levels: DEBUG, INFO, WARNING, ERROR, CRITICAL
`logging.disable()` function suppresses all log messages    
`logging.basicConfig()` function writes the log messages to a text file    

### Debugger
_Debugger_ allows you to execute your program one line at a time to track down bugs.    

| | | |
| --- | --- | --- |
| Continue | executes normally until it terminates or reaches a breakpoint |
| Step In | executes the next line of code and then pause again | step into the function and jump to the first line of code of that function |
| Step Over | executes the next line of code and then pause again | step over the function and executes lines of code at full speed until it returns from the current function|
| Step Out | executes lines of code at full speed until it returns from the current function |
| Stop | stops debugging entirely and not bother to continue executing the rest of the program |

Step Over = Step In -> Step Out    

_Breakpoints_ can be set on a specific line of code and forces the debugger to pause whenever the program execution reaches that line.    

## 12 - Web Scraping

| | | |
| --- | --- | --- |
| `requests` module | download files from the web without having to worry about issues such as network errors, connection problems, and data compression |
| `requests.get()` method | download a web page |
| `raise_for_status()` method | raise an exception if there was an error downloading the file and will do nothing if the download succeeded |
| `open( , 'wb')` function ... `write()` method | open the file in _write binary_ mode and write the binary data (in order to maintain the _Unicode encoding_ of the text |

### HTML (Hypertext Markup Language)
`BeautifulSoup` module

The `selenium` module lets Python directly control the browser by programmatically clicking links and filling in login information.
- Starting a browser
- Finding elements on the page
- Clicking the page
- Filling out and submitting forms
- Sending special keys
- Clicking browser buttons

## 13 - Working with Excel Spreadsheets
Microsoft Excel and Google Sheets        

- An Excel spreadsheet document is called a _workbook_.
- A single workbook is saved in a file with the _.xlsx_ extension.
- Each workbook can contain multiple _sheets or worksheets_.
- The sheet the user is currently viewing (or last viewed before closing Excel) is called the _active sheet_.
- _columns_, _rows_, _cell_

1. Import the `openpyxl` module
2. Call the `openpyxl.load_workbook()` function
3. Get a `Workbook` object
4. Use the `active` or `sheetnames` attributes
5. Get a `Worksheet` object
6. Use indexing or the `cell()` sheet method with `row` and `column` keyword arguments
7. Get a `Cell` object
8. Read the `Cell` object's `value` attribute

### Writing Excel Documents
- Creating and saving Excel documents
- Creating and removing sheets
- Writing values to cells
- Setting the font style of cells
- Adding formulas to cells
- Adjusting rows and columns (setting row height and column width)
- Merging and unmerging cells
- Freezing panes
- Creating charts using the data in a sheet's cells

## 14 - Working with Google Spreadsheets

- Obtaining Credentials and Token Files
- API

## 15 - Working with PDF and Word Documents
- PDF (Portable Document Format) .pdf and Word documents are binary files.

### PDF
- Extracting Text from PDFs
- Decrypting PDFs (some PDF documents have an encryption feature that will keep them from being read until whoever is opening the document provides a password)
- Creating PDFs
- Copying Pages
- Rotating Pages
- Overlaying Pages (with a logo, timestamp, or watermark)
- Encrypting PDFs
- Creating PDFs from Word Documents

### Word Document
- Reading Word Documents
- Getting the Full Text from a .docx File
- Styling Paragraph
- Creating Word Documents with Nondefault Styles
- Run Attributes (text)
- Writing Word Documents
- Adding Headings
- Adding Line and Page Breaks
- Adding Pictures

## 16 - Working with CSV Files and JSON Data
## 17 - Keeping Time, Scheduling Tasks, and Launching Programs
## 18 - Sending Email and Text Messages
## 19 - Manipulating Images
## 20 - Controlling the Keyboard and Mouse with GUI Automation
