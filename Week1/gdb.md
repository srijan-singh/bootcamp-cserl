# Debugging with GDB

## Exercises

### 1) Compile and run pointers.cpp. A segmentation fault will be observed. Use gdb to step through the program as it runs, and locate line of the program that causes this error and fix the bug.

- p is pointing to null and in cout value of null is causing segmentation fault

### 2) Compile and run fibbonaci.cpp. The program will run successfully. This program is meant to print the first n+2 terms of the Fibonacci sequence, where n is specified in line 6 of the program. However, the output of the code as given clearly does not match this requirement. A single logical bug in the code is causing this error. Use gdb to step through the program as it runs, locate and fix the bug.

- line 16, the sequence of assignment is causing error, last is being assigned first which is maling the second_last value exactly to be the last