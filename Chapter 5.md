## OER Chapter 5

## Objectives
Upon completion of this unit, students will be able to:
1. Describe predefined and user-defined functions
2. Identify value-returning functions, including actual and formal parameters
3. Construct and use a value-returning, user-defined function in a program
4. Identify function prototypes
5. Use void functions in a program
6. Distinguish between value and reference parameters
7. Compare and contrast local and global identifiers
8. Use static variables
9. Debug programs using drivers and stubs
10. Research function overloading
11. Use functions with default parameters


## Introduction

## A Section Per Topic

## Review Questions
1. A program that tests a function is called a _____ program.
  
2. TRUE/FALSE: When using a value-returning function, you must have a return type.

3. Formal parameters are ______ variables, while actual parameters _____ have to be variables
A.) never, always
B.) sometimes, always
C.) always do not
D.) sometimes, never

Answers 1. driver  2. True  3. C.) always do not

## Summary
  - A function in C++, much like a function in algebra, serves the purpose of computation, and with given numbers, the program will use the function to compute values.
  - Functions, also called modules, are like miniature programs that enable you to divide a program into manageable tasks.
  - Pre-defined functions are organized into libraries, and you can call them into your file by using header files such as iostream and cmath
  - Functions purpose also serve to increase the readability of the program by decreasing the complexity of the main
  - User-defined functions are classified into 2 categories: value-returning functions, which have a return type, or void functions, which do not have a return type
  - For value-returning functions, your program must have certain things such as the name of the function, the parameters, if any, the data type of each parameter, and the return type
  - The syntax of a value-returning function must be functionType functionName (formal parameter list) {
    statements
    }
  -  Formal parameters are always variables, while actual parameters do not have to be variables
  -  A function prototype informs the compiler about the intention to use a function, along with its return type, parameters, and name
  -  The syntax of a void function must be void functionName (formal parameter list) {
    statements
    } 
  - Reference parameters are used in three situations: when the value of the actual parameter needs to be changed, when you want to return more than one value from a function, or when passing the address would save memory space and time relative to copying a large amount of data
  - Local identifiers are declared within a function; these are not accessible outside of the function; global identifiers are declared outside of every function definition
  - Although it might seem smart to just declare all variables as global, problems can arise and problems caused by global variables in one area of a program might be misunderstood as problems caused in another area.
  - A static variable exists for the whole simulation; an automatic variable exists only for the lifetime of the task, function, or block
  -  In a complex program, you can write a separate program to test the function, called a driver program
  -  A stub is a function that is not fully coded
  -  When several functions have the same name, this is called function overloading; this is used when you have the same action for different data sets
## Key Terms
Value-Returning Functions - Functions that return values that are defined with a return type. These functions use the return statement to provide a value of a data type. It's worth noting that in all the programs we've encountered this far, the main function consistently utilizes a return statement to return the value 0.
Void VaFunctions - Functions that do NOT have a return type. Since there is no return type, the function doesn't use a return statement to return a value.
Data type - The return type of a value-returning function. Example: a function returning a string variable means the function's returning data type is a string.
Return statement - A return statement basically returns the value of a value-returning function via the "return ..." statement outside of the function. An example would be when you need a value that is computed in one function to be shared into a seperate function.
Function Prototype - A function head that has no body, leaving only what the general function is supposed to be without including the specifics of what that function is doing. A function prototype is NOT the definition of a function. It provides the name, data type, the included number(s), and the function's return value type. It is supposed to be the bare minimum to allow the C++ program to use the function. The function will be fully defined later in the program when needed.
Value Parameters - Parameters that are a copy of the value of an actual parameter. Basically, value parameters are used to provide a copy of another parameter so the value can be used without changing the original parameter's value.
Reference Parameters - These functions basically know the exact memory address of the original parameter, so it can use and/or manipulate the original value without having to copy the original parameter. These are best used when you don't want to copy large amounts of data.
Local Variables - Variables that are declared and used only within the body of a certain function. These variables are "local" because they are only used within a certain function and nowhere else, therefore making it "local" to the function the same way you are local to your hometown (function), not exactly to your planet (entire code).
Local Identifier - Identifiers declared within a function or block. These are not accessible outside of the function it's local to.
Global Identifier - Identifiers declared outside of all function definitions.
Nested Block - A block declared within another block, like how a nested if-statement is an if-statement inside another if-statement.
External Variable - A variable declared within a function that is also declared elsewhere in the code. These are declared by typing "extern (data type) (variable)".
Automatic Variable - A variable that is allocated memory space once a block is entered and is then automatically deallocated memory space once the block is exited.
Driver Program - A program that is designed to test a function. These are best for troubleshooting and better understanding how well your code is working.
Function Overloading - When you create several functions with the same name, but they have different formal parameter lists.


## Programming Exercises



## References
Functions in C++. (2015, June 20). GeeksforGeeks. https://www.geeksforgeeks.org/functions-in-cpp/
D. S. Malik. (n.d.). C++ ProgrammingFrom Problem Analysis to Program Design, 008th Ed
What’s the difference between declaring functions before or after main()? (n.d.). Stack Overflow. Retrieved April 1, 2024, from https://stackoverflow.com/questions/21718361/whats-the-difference-between-declaring-functions-before-or-after-main
Use of void function? - C++ Forum. (n.d.). Cplusplus.com. Retrieved April 1, 2024, from https://cplusplus.com/forum/beginner/242392/
EDA Playground. (n.d.). www.edaplayground.com. Retrieved April 1, 2024, from https://www.edaplayground.com/x/4yxv

‌## Editor
Andrew Ritter
