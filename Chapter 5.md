'## OER Chapter 5

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



## Programming Exercises



## References
Functions in C++. (2015, June 20). GeeksforGeeks. https://www.geeksforgeeks.org/functions-in-cpp/
D. S. Malik. (n.d.). C++ ProgrammingFrom Problem Analysis to Program Design, 008th Ed
What’s the difference between declaring functions before or after main()? (n.d.). Stack Overflow. Retrieved April 1, 2024, from https://stackoverflow.com/questions/21718361/whats-the-difference-between-declaring-functions-before-or-after-main
Use of void function? - C++ Forum. (n.d.). Cplusplus.com. Retrieved April 1, 2024, from https://cplusplus.com/forum/beginner/242392/
EDA Playground. (n.d.). www.edaplayground.com. Retrieved April 1, 2024, from https://www.edaplayground.com/x/4yxv

‌## Editor
Andrew Ritter
