# Aim:
To study basics of pointers


## Theory:


Definition:

A pointer is a variable that stores the memory address of another variable. 
It does not hold any actual data value like a normal variable, instead holds the location where the data is stored in memory. 
Pointers allow for efficient array and memory management, and can be used to directly manipulate memory.
Using pointers significantly improves performance for repetitive operations, like traversing iterable data structures (e.g. strings).
In particular, it is often much cheaper in time and space to copy and dereference pointers than it is to copy and access the data to which the pointers point.

Features of Pointers

An array, of any type, can be accessed with the help of pointers, without considering its subscript range.
Pointers are used for file handling.
Pointers are used to allocate memory dynamically.
Advantages of Pointers

Memory efficiency: Pointers allow for memory-efficient data sharing between different parts of a program.
Improved performance: Pointers can help reduce code and improve program performance.
Multiple values: Pointers allow programmers to return multiple values from a function.
Data structure building: Pointers can be used to build complex data structures like linked lists, trees, and graphs

## Algorithm:

1.Start

2.Initialize Variables

3.Declare an integer variable a and assign it a value of 10.

4.Declare a pointer variable aptr of type int* and assign it the address of variable a.

5.Print the value pointed to by aptr using cout. This will display the value of a.

6.Print the address stored in aptr using cout.

7.Print the address of a directly using cout.

8.End
