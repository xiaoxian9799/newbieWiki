# Methods
aka Functions

- [Declaring a method](https://github.com/xiaoxian9799/newbieWiki/blob/main/Methods.md#declaring-a-method)
- [Calling a method](https://github.com/xiaoxian9799/newbieWiki/blob/main/Methods.md#calling-a-method)

## Declaring a method
```
return_type name(input_data_type input_parameters, ...) // method signature
{
  method_definition
};
```

Example:
```
void SayHello();
```

`void` = the method returns no data

## Calling a method
```
method_name(input_parameters);
```

- [ ] Parameter vs Argument
- `parameter` = the variable in the method signature
- `argument` = the value passed when the method is called

  

> [!NOTE]
> C#    
> A method can be called before or after its definition.

`return` terminates execution of its method and returns control to the caller.

## Method Scope
Scope is the region of a program where certain data is accessible.

Global variables

## Parameters passed by value vs Parameters passed by reference
- [Data Types](https://github.com/xiaoxian9799/newbieWiki/blob/main/Data%20Types.md#data-types)



> [!NOTE]
> C#    
> Although `string` is a reference type, but it is _immutable_ (once it has been assigned a value, it can't be altered).
> When methods and operators are used to modify a string, the result that is returned is actually a new string object.


- Named arguments allow you to specify the value for a parameter using its name rather than position.
- Optional parameters allow you to omit those arguments when calling the method.
