# Python Stack Overflow Error

This repository demonstrates a common Python error: a stack overflow caused by an improperly designed recursive function.  The `bug.py` file contains code that causes the error, while `bugSolution.py` offers a corrected version.

**Error:**

The recursive function `my_function` lacks a proper base case for termination, creating an infinite loop of recursive calls. This exhausts the call stack, resulting in a `RecursionError: maximum recursion depth exceeded`. 

**Solution:**

The solution implements an iterative approach to calculate the sum, avoiding recursive calls. This method prevents the stack overflow and provides a more efficient solution for large inputs. 