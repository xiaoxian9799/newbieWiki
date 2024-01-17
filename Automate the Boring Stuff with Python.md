# Automate the Boring Stuff with Python
Reference: https://automatetheboringstuff.com/

## Table of Contents   
**Part I: Python Programming Basics**        
- [X] [Introduction](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#introduction)      
- [X] [01 - Python Basics](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#01---python-basics)      
- [X] [02 - Flow Control](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#02---flow-control)      
- [X] [03 - Functions](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#03---functions)      
- [ ] [04 - Lists](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#04---lists)      
- [ ] [05 - Dictionaries and Structuring Data](https://github.com/xiaoxian9799/newbieWiki/blob/main/Automate%20the%20Boring%20Stuff%20with%20Python.md#05---dictionaries-and-structuring-data)      
- [ ] [06 - Manipulating Strings]

**Part II: Automating Tasks**    
[07 - Pattern Matching with RegEx]    
[08 - Input Validation]    

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

## 04 - Lists

## 05 - Dictionaries and Structuring Data

