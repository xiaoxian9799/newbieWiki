# Code Verification

## Testing
### Functional vs Nonfunctional
- Functional testing: unit testing, integration testing, system testing, acceptance testing
- Nonfunctional testing: security testing, performance testing, usability testing, compatibility testing

## Debugging
Debuggers enable you to pause your application, step through your code line-by-line, and observe the state of variables and function parameters.

## Exception Handling
The process that a developer uses to manage those runtime exceptions (errors that occur while the application is running) within their code.
Errors that occur during the build process are referred to as errors, and aren't part of the exception handling process.

**Keyword:** _try, catch, finally_

Exceptions can be accessed and used to take corrective action when an error occurs in a program.

Common scenarios that require exception handling include:
- User input: code processes user input (input value is in the wrong format or out of range)
- Data processing and computations: code performs data calculations or conversions (code attempts to divide by zero, cast to an unsupported type, or assign a value that's out of range
- File input or output operations: code reads from or writes to a file (file doesn't exist, the program doesn't have permission to access the file, or the file is in use by another process)
- Database operations: code interacts with a database (database connection is lost, a syntax error occurs in a SQL statement, or a constraint violation occurs)
- Network communication: code communicates over a network (network connection is lost, a timeout occurs, or the remote server returns an error)
- Other external resources: code communicates with other external resources (web services, REST APIs, or third-party libraries)

```
try
{
  code that may generate an exception
}
catch
{
  code to handle an exception (log it or ignore it)
}
finally
{
  code to clean up resources that are allocated in a try block (code that executes whether an exception occurs or not)
}
```

`throw`

## Call Stack Unwinding
call stack

Runtime Exception
