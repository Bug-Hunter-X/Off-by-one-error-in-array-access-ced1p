# Off-by-one Error in C Array Access
This repository demonstrates a common off-by-one error in C and its solution.

## Bug
The file `bug.c` contains a simple C program that attempts to initialize an array of size 5.  However, the loop iterates one time too many, causing an out-of-bounds access and undefined behavior.

## Solution
The `bugSolution.c` file corrects this error by adjusting the loop condition to prevent accessing the array outside its valid indices.

## How to run
Compile and run both files using a C compiler (like GCC):

```bash
gcc bug.c -o bug
./bug

gcc bugSolution.c -o bugSolution
./bugSolution
```