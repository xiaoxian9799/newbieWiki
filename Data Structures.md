# Data Structures

## Array

### Declare A New Array and Assign Values to Elements of An Array

<details>

  <summary> C# </summary>
  
  ```C#
  string[] orderIDs = new string[3];  // create a new integer array with three elements
  
  orderIDs[0] = "A123";  // assign value to first element of the array
  orderIDs[1] = "B456";
  orderIDs[2] = "C789";
  ```
  
  ```
  string[] orderIDs = {"A123", "B456", "C789"};  // declare the array initialize values in a single statement
  ```
  
</details>

> [!TIP]
> **C#**
> 
> data_type[ ] array_name = new data_type[num_of_elements];    
> array_name[ nth_num_of_elements ] = values_assigned;    
> 
> data_type[ ] array_name = { values_assigned };

### Use the Length Property of An Array

<details>

  <summary> C# </summary>
  
  ```
  orderIDs.Length
  ```

</details>

| Array Methods || C# |
| --- | --- | --- |
| Sort( ) || Array.Sort(array_name); |
| Reverse( ) || Array.Reverse(array_name); |
| Clear( ) | Removes the contents of specific elements in your array and replace it with the array default value (`string` = `null`; `int` = `0`) | Array.Clear(array_name, index, length);
| Resize( ) | Adds or removes elements from your array. | Array.Resize(`ref` array_name, length) |
| Split( ) | | string_name.ToCharArray( ) or string_name.Split(',') |
| Join( ) || String.Join("-", array_name) |

> [!NOTE]
> null = a value that indicates a variable points to nothing in memory.

## Stack
