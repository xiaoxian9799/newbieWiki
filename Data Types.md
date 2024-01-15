# Data Types

**Definition:** A way a programming language defines how much memory to save for a value.

Bit = 0 or 1      
1 Byte = 8 Bits

## Values Types vs Reference Types

| Data Types | Value Types | Reference Types |
| --- | --- | --- |
| | Store the value directly | Store the address of the value |
| Memory Storage Area | Stack | Heap |
| Memory Storage Size | Smaller values | Larger values |

- [ ] Stack vs Heap

| Value Types | |
| --- | --- |
| `char` |
| `bool` | for `true` or `false` values |
| `int` | for most whole numbers |
| `decimal` | for numbers representing money. absolute precision. | 
| `float` | 
| `double` | for geometric or scientific purposes. used frequently when building games involving motion | 

| Reference Types | | Examples |
| --- | --- | --- |
| Arrays || data_type[ ] array_name = `new` data_type[num_of_elements]; |
| Classes ||
| String | for alphanumeric value | `string` string_name = " "; |

## Data Type Casting & Conversion
Error:
- cause an exception at runtime
- result in a loss of information (_Narrowing Conversion_)

Cast operator `( )`      
Example: (data_type)variable_name

- [ ] Implicit Conversion vs Explicit Conversion

### Widening Conversion vs Narrowing Conversion
Widening Conversion = You're attempting to convert a value from a data type that can hold _less_ information to a data type that can hold _more_ information.    
Example: `int` --> `decimal`    

Narrowing Conversion = You're attempting to convert a value from a data type that can hold _more_ information to a data type that can hold _less_ information.    
Example `decimal` --> `int` or `decimal` --> `float`     

`ToString( )` : number --> `string`    
`TryParse( )` : `string` --> `int`    
`Convert.ToInt32( )` : `decimal` --> `int` // rounds up or down

```
string value = "99";
int result = 0;
if(int.TryParse(value, out result)) // return type = `bool`
{
  Console.WriteLine($"Conversion succeeded: {result}");
}
else
{
  Console.WriteLine($"Conversion failed...");
}
```

