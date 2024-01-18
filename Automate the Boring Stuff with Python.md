# Automate the Boring Stuff with Python
Reference: https://automatetheboringstuff.com/

## Table of Contents   
**Part I: Python Programming Basics**        
- [X] [Introduction](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#introduction)      
- [X] [01 - Python Basics](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#01---python-basics)      
- [X] [02 - Flow Control](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#02---flow-control)      
- [X] [03 - Functions](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#03---functions)      
- [X] [04 - Lists](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#04---lists)      
- [X] [05 - Dictionaries and Structuring Data](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#04---lists)    
- [ ] [06 - Manipulating Strings](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#06---manipulating-strings)

**Part II: Automating Tasks**    
- [ ] [07 - Pattern Matching with RegEx](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#07---pattern-matching-with-regex)    
- [ ] [08 - Input Validation](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#08---input-validation)    
- [ ] [09 - Reading and Writing Files](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#09---reading-and-writing-files)
- [ ] [10 - Organizing Files](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#10---organizing-files)
- [ ] [11 - Debugging](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#11---debugging)
- [ ] [12 - Web Scraping](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#12---web-scraping)
- [ ] [13 - Working with Excel Spreadsheets](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#13---working-with-excel-spreadsheets)
- [ ] [14 - Working with Google Spreadsheets](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#14---working-with-google-spreadsheets)
- [ ] [15 - Working with PDF and Word Documents](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#15---working-with-pdf-and-word-documents)
- [ ] [16 - Working with CSV Files and JSON Data](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#15---working-with-pdf-and-word-documents)
- [ ] [17 - Keeping Time, Scheduling Tasks, and Launching Programs](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#17---keeping-time-scheduling-tasks-and-launching-programs)
- [ ] [18 - Sending Email and Text Messages](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#18---sending-email-and-text-messages)
- [ ] [19 - Manipulating Images](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#19---manipulating-images)
- [ ] [20 - Controlling the Keyboard and Mouse with GUI Automation](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#20---controlling-the-keyboard-and-mouse-with-gui-automation)

## Introduction <!-- 20240117 -->
- Examples of _operating system_: Microsoft Windows, Linux OS, Apple macOS, Apple iOS, Google's Android OS   
- The _interactive shell_ is good for _running or executing_ Python _instructions_ one at a time (by using >>> _prompt_), whereas _file editor_ is good to write instructions for the entire Python programs.
- Both _compiler_ and _interpreter_ translate _source code_ (that adhere to _syntax rules_) into machine code. Compiler translates code at once before the program runs, whereas interpreter translates code line-by-line as the program runs.    
- Writing programs involves breaking down a problem into individual, detailed steps.     
  
_debugging_    

_built-in functions_    
_standard library_    
A _module_ is a Python program that contains a related group of functions that can be embedded in your programs.    

```Python
  import module_name, ...
  module_name.func_name()

  from module_name import *
  func_name()
```

## 01 - Python Basics <!-- 20240117 -->
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

## 02 - Flow Control <!-- 20240117 -->
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

## 03 - Functions <!-- 20240117 -->
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

## 04 - Lists  &  05 - Dictionaries and Structuring Data <!-- 20240118 -->

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

## 06 - Manipulating Strings <!-- 20240118 -->
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

## 07 - Pattern Matching with RegEx  
## 08 - Input Validation    
## 09 - Reading and Writing Files
## 10 - Organizing Files
## 11 - Debugging
## 12 - Web Scraping
## 13 - Working with Excel Spreadsheets
## 14 - Working with Google Spreadsheets
## 15 - Working with PDF and Word Documents
## 16 - Working with CSV Files and JSON Data
## 17 - Keeping Time, Scheduling Tasks, and Launching Programs
## 18 - Sending Email and Text Messages
## 19 - Manipulating Images
## 20 - Controlling the Keyboard and Mouse with GUI Automation
