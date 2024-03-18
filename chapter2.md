# OER CHAPTER 2

## OBJECTIVES
After completing this chapter, students will be able to:

    Identify input and output streams
    Read data from the standard input device
    Describe input stream functions get, ignore, putback, and peek
    Write data to the standard output device
    Use manipulators in a program to format output
    Perform input and output operations using the string data type
    Read data from a file (include examples)
    Write data to a file (include examples)

## Introduction
In Chapter 2, much of of C++'s input/output (I/O) basics were covered. Things like using cin and cout 
to handle data coming in and going out of your program were explained and examples of how this works were shown. 
This chapter goes deeper into the world of I/O operations. You'll explore statements that grab input from the standard 
input device and showcase output on the standard output device. Plus, you'll learn about formatting output using manipulators, 
which will add some some formatting and stylingn to to your program's results. You'll also discover the limits of standard 
I/O operations and how to break free from them. In short, this chapter goes deep into the details of using I/O devices in C++ code.

## A Section Per Topic
Comments: Used to identify the authors of the program, give the dates whem its modified, and give a brief explanation of the program. These
are designated by using '//' before the line of comment
Special symbols: The smallest unit for a program written in ant langauge is a token. Thry are divded into symbols, word symbols, and identifiers 
Keywords: Words or symbols that cannot be used for anything but their intedned use. 
Identifiers: The names of things that appear in programas such as: variables, constants, and functions. 
White spaces: They seperate special symbols, reserved words, and identifiers.
Data types: A set of vaules together with a set of allowed operations.
Intergal: Data type that deals with intergers or numbers without a decimal place 
Floating point: data type that deals with deciaml numbers
Enumeration: A user defined data type 
Type conversion: Used to aviod type coercion by providing explicit type conversion through the use of a cast operator 
String: A sequence of zero or more characters.
Syntax: Syntax of language tells what is legal and what isn't. 
Statement Terminator: The semi colon must end all C++ statements. 

## Review Questions 
1. True/False: When using cin and cout you must #include <iostream> in the header.
2. In C++ , an infinite sequence of characters from a source to a destination is considered a ________.
3. Which is not a manipulator?
a) cin
b) setw
c) showpoint
d) fixed

** Answers 1. True 2. stream 3. a) cin

## Summary
-To use cin and cout, the program must include the header file iostream.
-Because cin and cout are already defined and have specific meanings, you should never redefine them in programs to avoid confusion.
-The extraction operator >> is binary and thus takes two operands. The left-side operand must be an input stream variable, such as cin. Because the purpose of an input statement is to read and store values in a memory location.
-cerr and clog are also output streams, so they essentially work like cout, with the only difference being that they identify streams for specific purposes: error messages and logging
-An input stream is a stream from a source to a computer, and an output stream is a stream from a computer to a destination.
-To use the manipulators setprecision, setw, and setfill, the program must include the header file iomanip.
-The function get is used to read data on a character-by-character basis and does not skip any whitespace characters.
-The function ignore is used to skip data in a line.
-The value of the expression intExp specifies the maximum number of characters to be ignored in a line.
-The variable cin can access the stream function get, which reads character data. The get function inputs the very next character, including whitespace characters, from the input stream and stores it in the memory location indicated by its argument.
-The function setw is a manipulator that formats the output of an expression in a specific number of columns; the default output is right-justified
-If the number of columns specified in the setw manipulator exceeds the number of columns required by the next expression, the output is right-justified. To left-justify the output, you use the manipulator left.
-The function putback puts the last character retrieved by the function back into the input stream.
-The function peek returns the next character from the input stream but does not remove the character from the input stream.
-All preprocessor directives begin with #, and only white-space characters may appear before a preprocessor directive on a line. Preprocessor directives are not C++ statements, so they do not end in a semicolon (;).
-Attempting to read invalid data into a variable causes the input stream to enter the fail state.
-Once an input failure has occurred, you use the function clear to restore the input stream to a working state.
-The header file fstream contains the definitions of ifstream and ofstream. Ifsteam meaning in and ofstream meaning out.
-A single quotation mark is a digit separator.

## Key Terms
Stream
        : An infinite sequence of characters from a source to a destination
Cin
        : The common input
Cout
        : The common output
Setw
        : A manipulator that formats the output of an expression in a specific number of columns; the default output is right-justified
Pow
        : The pow function can be used to calculate x^y in a program, from the form (x,y)
Putback
        : Puts the last character retrieved by the function back into the input stream
Peek
        : Peek returns the next character from the input stream but does not remove the character from the input stream.
Fixed
        : A manipulator that outputs floating-point numbers in the fixed decimal format.
Showpoint
        : A manipulator that outputs floating-point numbers with a decimal point and trailing zeros.
Preprocessor
        : Gives instructions to the compiler to preprocess the information before actual compilation starts.

## Programming Excersices

This program is supposed to display the product of n multiplied by n - 1. Find the logic and syntax errors. 



    #include <iostream>
    int main() {
    int n;

    cout << "Enter a positive integer: "
    cin >> n;

    
    int result = n * (n + 1);  

    cout << "The product of " << n << " and " << n - 1 << " is: " << result << :endl;

    return 0;
    }

Write a program that allows the user to input the temperature in Celsius and outputs the temperature in Kelvin and Fahrenheit. 


## References
Basic Input/Output. Cplusplus. https://cplusplus.com/doc/tutorial/basic_io/
Manipulators in C++ with Examples. GeeksForGeeks. https://www.geeksforgeeks.org/manipulators-in-c-with-examples/
C++ Preprocessor. Tutorialspoint. https://www.tutorialspoint.com/cplusplus/cpp_preprocessor.html
