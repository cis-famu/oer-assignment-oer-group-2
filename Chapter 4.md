## OER Chapter 4

## Objectives
Upon completion of this unit, students will be able to:
1. Identify the need for repetition control structures
2. Distinguish the use of While loops including For, Do, EOF
3. Write If and Else statements
4. Test break and continue statements
5. Build nested control structures
6. Identify methods to prevent bugs and debug loops

## Introduction

## A Section Per Topic

## Review Questions
1. Which of the following loops checks the condition after the code is executed once?
A.) For Loop
B.) Do-While Loop
C.) Flag-Controlled Loop
D.) Sentinel-Controlled Loop

2. To leave a loop or switch statement, you use _____.

3. True/False: In a for loop, if the initial condition is not met, then the loop body will not be executed,

Answers 1. A 2 Break 3. True
## Summary
- A while loop is structured with the condition before the statement, and the statement will not be executed unless the condition is met
- A do-while loop is structured by the statement before the condition and therefore, the statement will run once no matter what and then will check the condition to see whether it will run again.
- A counter-controlled Loop is a while loop that specifies a specific number, and the loop will count until it reaches the specified number
- A sentinel-controlled loop is a type of while loop that specifies a specific number, and the loop will count until it reaches the specified number
- A flag-controlled loop is a while loop that is controlled by a boolean variable, and the loop ends when the boolean is no longer true
- An EOF-controlled loop is a while loop that checks if the end of the file has been reached and while run until it is reached
- The EOF function can be used with files to ensure that the program reads through the end of the file
- A nested control structure is when (inner) control structures are placed within another (outer) control structure.
- A for loop is a programming construct that iterates over a sequence of elements, executing a block of code for each iteration. It typically consists of an initialization step, a condition to check before each iteration, and an update step. The loop continues until the condition evaluates to false, allowing for efficient repetition and automation in code execution.
- A do-while loop is a control structure that executes a block of code at least once before checking a condition for continuation. If the condition evaluates to true, the loop repeats; otherwise, it terminates, providing a guarantee of at least one execution of the code block.
- To avoid issues with a counting loop being off by one value, (A.K.A. the "Off by One" problem), ensure that you have the loop control variable assigned to the right value.
- Having a loop execute the right noumber of times can be fixed with that one simple change rather than having to add more lines of code, which may slow down the program and add unnecessary commands.
- Debugging is an essential part of programming, requiring careful attention to syntax and logic errors.
- Techniques like hand-tracing or using debuggers help verify algorithms, especially for loops where off-by-one errors are common, and understanding loop variations helps in ensuring program correctness.
- If debugging becomes tedious and too challenging, it may be more efficient to start over from square one rather than persisting with a flawed program.
## Key Terms
Break
    : This keyword is used to immediately exit the loop or switch case it is placed in
Continue
    : This keyword skips the rest of the code in the current iteration and proceeds with the next iteration of the loo
Nested Loop
    : These are loops within loops. They are useful for iterating over multidimensional structures, such as matrices, or for performing complex tasks that require a loop to be executed multiple times for each iteration of an outer loop
For loop
    : This is a more compact loop, in the parameters it includes the initialization, condition and update statement.
Do-while loop
    : Structured by the statement before the condition and therefore, the statement will run once no matter what and then will check the condition to see whether it will run again.
While loop
    : Structured with the condition before the statement, and the statement will not be executed unless the condition is met
Counter-Controlled Loop
    : Specifies a specific number and the loop will count until it reaches the specified number
Sentinel
    : A special value assigned to end a while loop when it is encountered
Flag controlled loop
    : A while loop controlled by a boolean variable, and the loop ends when the boolean is no longer true
EOF-Controlled Loop
    : EOF stands for End Of File, and this is a while loop that checks if the end of the file has been reached and while run until it is reached
EOF function
    : This is used to esure the program has reached the end of a file
## Programming Exercises

## References
GeeksforGeeks. (2017, January 13). C++ Loops. GeeksforGeeks. https://www.geeksforgeeks.org/cpp-loops/
C++ Nested Loop (With Examples). (n.d.). Www.programiz.com. Retrieved March 8, 2024, from https://www.programiz.com/cpp-programming/nested-loops#google_vignette
C++ Break and Continue. (n.d.). Www.w3schools.com. https://www.w3schools.com/cpp/cpp_break.asp

‌# Editor
Andrew Ritter / cam telfair
