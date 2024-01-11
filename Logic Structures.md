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
 
  **Keywords:** _for, while, foreach, loop, repetition_   
  **Description:**   
  - The `for` statement iterates through a code block a specific number of times. (initializer, condition, iterator)
  - The `while` statement iterates through a block of code until a condition is met.
  - The `foreach` statement iterates through a block of code once for each item in a sequence of data like an array or collection.
  
  **Examples:**    

  ```
  C#

  string[] names = {"A", "B", "C"};

  for(int i = 0; i < names.Length; i++)
  {
    Console.WriteLine(names[i]);
  }

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
  
</details>

**Remarks:**  

### 
