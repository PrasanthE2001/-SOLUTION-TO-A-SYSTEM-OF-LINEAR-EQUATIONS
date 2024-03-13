# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: E prasanth
#RegisterNumber: 212221233002

import numpy as np
A = np.array([[1, -3],[3, 1,]])
b = np.array([0, 10])
x = np.linalg.solve(A, b)
print(x)
```
## output:
![Screenshot (10)](https://github.com/PrasanthE2001/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/114572171/85798e6f-be97-40e9-90dd-7d1d8a966dc2)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program.
