# OER CHAPTER 3

## OBJECTIVES
After completing this chapter, students will be able to:

1. Identify and use control structures
2. Identify logical and relational operators, how they work, and the order of precedence
3. Distinguish the relationship of relational operators and simple data types
4. Identify how to form and evaluate logical (Boolean) expressions
5. Use one-way and/or two-way selection syntax
6. Demonstrate a switch statement in a program

##Introduction

In Chapter 3, we review the basic concepts of functions, different types of functions, and their specific uses for C++. As well for functions, 
we also go over different operators such as the equality operator, assignment operator, or the Boolean operator. 
The equality operator determines if two expressions are equal. The Boolean operator determines if the specific 
value is true or false. Furthermore, we go over logical expressions, which are expressions that evaluate true or false values in code. 
It also decides whether or not to execute the state. Moreover, people reading this chapter will be introduced to relationships between data types
and relational operators and demonstrate different statements in the program.
## A Section Per Topic

Relational Operations in c++: c++ allows the use of mathematical inequalities (>, >= meaning ‘greater than or equal to’, <, <= meaning ‘less 
than or equal to’) as well as two new operands (== ‘meaning equal to’, !== meaning ‘not equal to’). The placement of the equal signs on the 
greater/less than or equal to do matter.

Comparing Characters: Alphabetical characters can be compared to using mathematical inequalities. The later the character is in the alphabet, 
the higher its value (ex: z > a).

One-Way Selection: Statements that do something based on one condition. If the conditional is true, something is done. If the conditional is 
false, nothing is done.

Two-Way Selection: Similar to one-way selection, but if the conditional is false, something else is done.

int Data Type and Boolean Expressions: Because booleans store their value (true or false) as int variables (1 = true, 0 = false), you can 
manipulate expressions that produce a true or false result by putting the expression as an input to an int variable. If a boolean expression
is false, the int variable will be assigned 0 and 1 if it’s true.

Logical Operators: Booleans can have multiple statements that influence whether or not a boolean is true or false. ‘&&’ means ‘and’ and will 
only be true if both expressions are true. ‘| |’ means ‘or’ and is only true if one or both expressions are true. Finally ‘!’ 
means ‘not’ and is true if the expression is false and vice versa.

Order of Precedence: Logical expressions have an order of precedence. ‘!, +, -’(as unary operators) first, ‘*,/,%’ second, ‘+,-’ third, ‘<, <=, >, >=’
fourth, ‘==, !=’ fifth, ‘&&’ sixth, ‘| |’ seventh, ‘= (assignment operator)’ last.

Nested If Statements: A statement that consists of multiple smaller if statements within it. A compound if statement would be one big if statement
whose 1st if checks an argument, then the 2nd if statement within it starts with ‘else’ instead of if and continues using else until satisfied. 
This is better than writing multiple if statements in a row because you use less space, time, and characters.

Nested Ifs vs. Multiple If Statements: Nested if statements will normally run quicker and more efficiently because the program will only 
execute the if statement that is true and will leave the nested if. If they weren’t nested, the program will execute all statements if
they are true.

A Warning on Comparing Floating-Point Numbers: Floating-point numbers in computers are represented in binary, which can result in rounding
errors and precision issues due to their finite representation. When comparing floating-point numbers for equality, small differences in 
the least significant bits may lead to unexpected results, making direct equality comparisons unreliable. Therefore, it's often recommended
to use tolerance thresholds or comparison techniques that consider the acceptable range of difference instead of strict equality checks. 
You can do this by checking if the absolute difference between the values is less than a certain threshold (such as 0.0001).

A Warning on Associativity of Relational Operators: Be careful how you put in logical expressions! If you were to put in an expression 
‘0 <= num <= 10’, any positive number would make that boolean true, even numbers that aren’t within 0 and 10. This is because relational
operators are evaluated from left to right. Any positive number is greater than 0. This then makes ‘0<=num’ equal 1, and 1 is less than 10.
A better way of putting this in is ‘0 <= num && num <= 10’.

Input Failure and the If Statement: To ensure that if statements are accurate and running properly, make sure that the if statement(s) is
reading from defined variables and the file(s) that it’s reading have the required text or values within them. Like other functions,
if an if statement doesn’t work properly, it can send the entire program into a failed state. Another way if statements can fail is if the
logical expression in it is logically incorrect or creates a syntax error; it will most times make the if statement true and therefore
act as if it is true.

Confusion between the Equality Operator (==) and the Assignment Operator (=): The equality operator (==) is a comparison operator used for
decision-making processes like (if num == 10), while the assignment operator is exclusively used for assigning a value to a variable. If you
use these interchangeably, it will disrupt the program or stop it from running entirely.



## Review Questions

1. True/False: These control statements enable you to determine the order in which the statements are executed

2. which of the following describes this statement: "A logical expression that allows the statement to be either true or false

A. Cin 
B. Boolean expression
C. Logical statement
D. switch structure 

3. Fill in the blank: Relational and logical expressions are evaluated from...

## Summary
-In C++, the symbol ==, which consists of two equal signs, is called the equality operator. This differentiates from the previous assignment operator we knew as a single = sign.
-The equality operator determines whether two expressions are equal, whereas the assignment operator, =, assigns the value of an expression to a variable.
-When comparing characters the values increase with the alphabet but lowercase letters have larger values than uppercase letters.
-In a one way selection, if an expression is true, then the statement executes, but if it is not true, then the statement does not execute
-If the semicolon immediately follows the closing parenthesis, the if statement will operate on the empty statement.
-In a 2-way selection, if the value of the expression is true, statement1 executes. If the value of the expression is false, statement 2 executes
-In C++, int variables can be used to store the value of a logical expression.
-In C++, bool variables can store the value of a logical expression.
-Boolean operators enable you to combine logical expressions.
-In C++, & and | are also operators. The meaning of these operators is different from the meaning of && and ||. Using & in place of && or | in place of || might result in a typographical error
-Relational and logical operators are evaluated from left to right
-There is no stand-alone else statement in C++. Every else has a related if. An else is paired with the most recent if that has not been paired with any other else.
-Boolean expressions can be manipulated or processed in either of two ways: by using int variables or by using bool variables.
-In a sequence of if-else statements, if more than one condition is true, only the statements associated with the first true condition will be executed. On the other hand, in a series of if statements, such as (b), if more than one condition evaluates to true, statements associated with each true condition will execute.
-To permit more complex statements, C++ provides a structure called a compound statement or a block of statements. This is done by enclosing between curly braces, { and }.
-When C++ evaluates a logical expression, any nonzero value is treated as TRUE
-In C++, switch, case, break, and default are reserved words
-The expression is sometimes called the selector. 
-If certain conditions are not met, the program can be terminated using the assert function.
-Executing a break statement in a switch statement immediately exits the switch structure.
-One way to address possible input failure is to check the status of the input stream variable. You can check the status by using the input stream variable as the logical expression in an if-else statement. If the last input succeeded, the input stream variable evaluates to true if it is not it evaulates to false. 
- Values of type int other than 0 can also be returned to the operating system via the return statement. The return of any value other than 0, however, indicates that something went wrong during program execution.

## Key Terms
Logical expression
-An expression that evaluates to true or false is called a logical expression.
Decision maker
-Decides whether to execute the statement that follows it
Boolean operator
-Enable you to combine logical expressions.
Nested
-When one control statement is located within another
Short-circuit evaluation
-A process in which the computer evaluates a logical expression from left to right and stops as soon as the final value of the expression is known.
Conditional Operator
-A ternary operator, which means that it takes three arguments
Pseudocode
-A method involves using an informal mixture of C++ and ordinary language
Assert
-If certain conditions are not met in a program, the program can be terminated
Switch structure
-This is used to handle multiway selection.

## Programming Exercises

## References
Relational Operators, Rebus Press, https://press.rebus.community/programmingfundamentals/chapter/relational-operators/
Understanding Python If-Else Statement, Simplilearn, 5/18/23, https://www.simplilearn.com/tutorials/python-tutorial/python-if-else-statement
JavaScript Switch Statement, W3schools, https://www.w3schools.com/js/js_switch.asp
Editor: Andrew Ritter
