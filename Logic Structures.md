# Logic Structures

**Keywords:** _sequential, conditional, iteration_   
**Languages:**

<details>
  <summary> Sequential </summary>   
 
  **Keywords:**   
  **Description:**   
  **Examples:**   
  **Remarks:**   
  
</details>

<details>
  <summary> Conditional </summary>   
 
  **Keywords:** _if-elseif-else, switch-case, selection_    
  **Description:**   
  **Examples:**   

  ```
  C#

  int employeeLevel = 100;
  string title = "";

  if(employeeLevel == 100){

  }
  else if(employeeLevel == 200){
    title = "Senior Associate";
  }
  else if(employeeLevel == 300){
    title = "Manager";
  }
  else if(employeeLevel == 400){
    title = "Senior Manager";
  }
  else{
    title = "Associate";
  }
  ```
  

  ```
  C#

  int employeeLevel = 100;
  string title = "";

  switch(employeeLevel)
  {
    case 100:
    case 200:
      title = "Senior Associate";
      break;
    case 300:
      title = "Manager";
      break;
    case 400:
      title = "Senior Manager";
      break;
    default:
      title = "Associate";
      break;
  }
  ```
  
  **Remarks:**   
  
</details>

<details>
  <summary> Iteration </summary>   
 
  **Keywords:** _for, while, loop, repetition_   
  **Description:**   
  **Examples:**   
  **Remarks:**   
  
</details>

### foreach

`C#`    
**Keywords:** _foreach, in_
```
string[] names = {"A", "B", "C"};
foreach(string name in names)
{
  Console.WriteLine(name);
}
```

Output:
```
A
B
C
```

### 
