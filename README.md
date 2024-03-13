# [Overview Of C]
- ## [Parameter passing technioues]


## Overview Of C
   - ### declaration 
       - ### simple variable
             int a;
       - ### pointer variable
             int *a;    \\ a is a pointer variable
       - ### array
             int a[9];  \\9 is the size of an array
   - ### initialization
       - ### simple variable
             int a=10;
       - ### pointer variable
             int a=10;
              *b=&a;
              Explanation :(If we write b then it will give the address of a ;if we write *b then it will give us the value which  is stored in variable a)
If we want to store the address of b in another variable say [d] then we will write as follows
**d=&b
       - ### array
             int a[9]={1,2,3,4,5,6,7,8,9};

## Pointer
    - 
## memory accessing for array
   - ### row major order(C++ Deploys by default)
In row-major order, the consecutive elements of a row reside next to each other in memory space .
   - ### column major order
In column major order, the elements of a column are stored adjacent to each other in the memory. The first element of the array (arr[0][0]) is stored at the first location followed by the arr[1][0] and so on. After the first column, elements of the next column are stored stating from the top.
## scoping 
   - ### static scoping
         -if a local variable is not present in that func/scope then it directly takes the value of free/ global variable. C++ uses Static scoping by default .
   - ### dynamic scoping
         -if local variable is not present in that func/scope then it  takes the value of that variable from the func from where it has been called(backtracking). Ex:
## Parameter passing technioues
   - Caller Function (A): The caller function, also known as the calling function or the client function, is the function that initiates the call to another function.
   - Called Function or Callee Function (B): The called function, also known as the callee function or the target function, is the function that is invoked or executed when called by another function.
   - Terminology
      - Formal Parameter: A formal parameter is like a variable declaration within the function or method’s prototype or definition. It specifies the name of the parameter and its data type. It serves as a placeholder for the actual value that will be passed when the function or method is called.
      - Actual arguments, also referred to as arguments or parameters
      - Actual Parameter: An actual parameter, on the other hand, is the real value or expression provided in the function or method call, which corresponds to a formal parameter. It is the concrete data that gets passed into the function or method when it is invoked.
      - Modes:
        - IN Mode: When a parameter is passed as IN, it means the caller is providing information to the callee. The callee can use this information but cannot modify the original value in the caller.
        - OUT Mode: When a parameter is passed as OUT, it means the callee can write or modify the value of this parameter, and those modifications will be reflected in the caller’s environment.
        - IN/OUT Mode: This combines both IN and OUT modes. The caller provides an initial value to the callee, and the callee can both use and modify the value, which will then be visible to the caller after the function or method call.

   - ### call by value
         - 
   - ### call by reference
         - 
   -### call by copy restore 



garbage collector
Garbage collection ensures that a program does not exceed its memory quota or reach a point that it can no longer function. It also frees up developers from having to manually manage a program's memory, which, in turn, reduces the potential for memory-related bugs.
type of matrix
spare matrix
A sparse matrix is a special case of a matrix in which the number of zero elements is much higher than the number of non-zero elements. As a rule of thumb, if 2/3 of the total elements in a matrix are zeros, it can be called a sparse matrix.
dense matrix
A matrix which has a high proportion of non-zero entries.

why indexing is starts with 0 in place of 1
It is so to mainly save the operational cost of running a program .It is less hectic to access the elements by computing the index and bit size of each data type by using 0 at starting of an index .The indexing that start from 0 saves one operation compared to 1 based indexing.

Mathematics operation 
Post increment/pre increment 
