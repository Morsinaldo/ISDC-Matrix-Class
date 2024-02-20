# Overview

The goal of this project is to implement a `Matrix` class in Python. Specifically, implement the following methods:

```python
class Matrix:
    def determinant(self):
        # your code

    def trace(self):
        # your code

    def inverse(self):
        # your code

    def transpose(self):
        # your code

    ## Overloaded operators

    def __add__(self,other):
        # your code
    
    def __sub__(self,other):
        # your code

    def __mul__(self,other):
        # your code
```
This is class is important to use in the Kalman Filter and it can be find in the [matrix.py](./matrix.py) file.

## Project Files

- **matrix.py** - This contains the beginnings of a Matrix class as well as some helper functions zeroes and identity. This is the file you will be doing most of your work in.
- **matrix_playground.ipynb** - A notebook that imports your Matrix class and calls the test code. You may find it useful to use this notebook as a place to use the matrix math code you will write in matrix.py.
- **matrix_cheat_sheet.ipynb** - A Jupyter notebook with a glossary, explanation of matrix notation and list of matrix equations. Use this as a reference when filling out the methods in the Matrix class!
- **kalman_filter_demo.ipynb** - You don't need to do anything with this notebook but you may find it interesting. Once your matrix class is working properly, the KF implemented here will actually work!

Other Files (feel free to ignore). 1. `test.py` - Contains test code which demonstrates the expected functionality of your code. 2. `datagenerator.py` - this just contains some helper code which is used by the Kalman Filter.

## Project Rubric

- **Methods pass all unit tests**: If your code passes the provided tests in test.py then your project will meet specification for this criteria.
- **determinant() works correctly**: `determinant()` of matrix is calculated the right way and we get the correct output.
- **trace() works correctly**: `trace()` of matrix is calculated the right way and we get the correct output.
- **inverse() works correctly**: `inverse()` of matrix is calculated the right way and we get the correct output.
- **T() works correctly**: `T()` (transpose) of matrix is calculated the right way and we get the correct output.
- **add() works correctly**: `add()` is calculated the right way and we get the correct output.
- **neg() works correctly**: `neg()` is calculated the right way and we get the correct output.
- **sub() works correctly**: `sub()` is calculated the right way and we get the correct output.
- **mul() works correctly**: `mul()` is calculated the right way and we get the correct output.
- **rmul() works correctly**: `rmul()` is calculated the right way and we get the correct output.

## Refereces

[Introduction to Self-Driving Cars NanoDegree](https://learn.udacity.com/nanodegrees/nd113)