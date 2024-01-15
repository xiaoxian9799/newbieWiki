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

- `parameter` = the variable in the method signature
- `argument` = the value passed when the method is called

  

> [!NOTE]
> C#    
> A method can be called before or after its definition.

`return` terminates execution of its method and returns control to the caller.

## Method Scope
Scope is the region of a program where certain data is accessible.

Global variables

