## OER Chapter 6

## Objectives
After completing this chapter, students will be able to:

  1. Identify the purpose of arrays
  2. Declare and initialize arrays
  3. Demonstrate manipulating data into arrays
  4. Distinguish the restrictions on array processing
  5. Pass an array as a parameter to a function
  6. Demonstrate how to search and sort an array
  7. Use auto declarations
  8. Evaluate range-based for loops
  9. Use C-strings to input data into—and output data from—a C-string
  10. Define parallel, two-dimensional, and multidimensional arrays



## Introduction

## A Section Per Topic

## Review Questions
1. In a two-dimensional array is stored in ______-_______ format
2. f
3. f

Answers 1) row-column 2)  3)
## Summary
- An array is a fixed number of components all of the same data type and adjacent memory space
- A one-dimensional array is where components are arranged in list form dataType arrayName[intExp];
- To access a component of an array, you use arrayName[indexExo]
- If the index is negative or greater than ARRAY_SIZE - 1, then we say that the index is out of bounds. This may cause an error in your code
- When initializing arrays as they are declared, it is unnecessary to specify the array size. The number of initial values in the braces determines the size. This would look like arrayName[]= {0,22.8,21.9}
- You can partially initialize an array ,but if you only put one number it initializes every component of the array to the value and if you only put a certain number of values it will initialize the components in order
- When declaring a one-dimensional array as a formal parameter, the size of the array is usually omitted. If you specify the size of a one-dimensional array when it is declared as a formal parameter, the size is ignored by the compiler.
- C++ does not allow functions to have an array be the return value.
- When initializing an array you may also use a variable to create the length of the array
- The most common use of an array is to search for a value using a sequential search using the function seqSearch and if it returns a value greater than or equal to 0, it is a successful search; otherwise, it is an unsuccessful search.
- Another common use of arrays is a selection sort which goes in order sorting a list of values putting the smaller one before the larger one until the list is in order
- The function strcmp compares its first C-string argument with its second C-string argument character by character.
- The length of the input C-string must be less than or equal to 30, whatever the length is set to the computer stores the length that is input and the null character '\0'
- If two or more arrays hold related information they are considered parrallel arrays
- Two dimensional arrays are usually used when information is provided in table format and the information is stored in row-column format
- To access the components of a two-dimensional array, you need a pair of indices: one for the row position (which occurs first) and one for the column position (which occurs second).
- When initiializing a two-dimensional array int must be arrayName[][] {{ , }
                                                                        { , }
                                                                        { , }}
- 
## Key Terms



## Programming Exercises



## References

‌## Editor
Andrew Ritter
