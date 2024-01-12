# String

## String Formatting
### Composite Formatting
### String Interpolation
**Definition:** A technique that simplifies _composite formatting_.    
`$` directive    

Example: 
```
C#

string first = "Hello";
string second = "World";
Console.WriteLine($"{first}{second}!");
```

Output:
```
Hello World!
```

| Format Specifiers | Description | Examples |
| --- | --- | --- |
| `:C` | currency | {var_name:C} |
| `:Nn` | include commas to delineate thousands, millions, billions, and so on, n = number of values displayed after the decimal point (default = 2) | {var_name:N4} |
| `:Pn` | percentages, n = number of values displayed after the decimal point | {var_name:P2} |

- Methods that add blank spaces for formatting purposes (`PadLeft()`, `PadRight()`)
- Methods that compare two strings or facilitate comparison (`Trim()`, `TrimStart()`, `TrimEnd()`, `GetHashcode()`, the `Length` property)
- Methods that help you determine what's inside of a string, or even retrieve just a part of the string (`Contains()`, `StartsWith()`, `EndsWith()`, `Substring()`)
- Methods that change the content of the string by replacing, inserting, or removing parts (`Replace()`, `Insert()`, `Remove()`)
- Methods that turn a string into an array of strings or characters (`Split()`, `ToCharArray()`)

- `IndexOf()` : string_name.IndexOf(char_or_str), returns `-1` if it can't find a match
- `Substring()` : string_name.Substring(start_position, optional_length)
- `IndexOfAny()` : string_name.IndexOfAny(array_name, optional_start_position), returns the first position of an array of char that occurs inside of another string
- `LastIndexOf()` : string_name.IndexOf(char_or_str), returns the last position of a character or string inside of another string

`constant` variable = a value that once initialized can never be changed
