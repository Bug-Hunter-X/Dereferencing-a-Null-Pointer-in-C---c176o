# Dereferencing a Null Pointer in C++
This repository demonstrates a common error in C++: dereferencing a null pointer.  Dereferencing a null pointer means trying to access the memory location pointed to by a pointer that has a value of 0 (or nullptr). This typically causes a segmentation fault (crash) or unpredictable behavior.

The `bug.cpp` file contains the problematic code. The `bugSolution.cpp` file shows how to avoid this error by checking if the pointer is valid before dereferencing it.