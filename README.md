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
#Developed by: ARVIND S
#RegisterNumber: 212222240012

import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
soln=np.linalg.solve(A,B)
print(soln)
```
## Output:

![Screenshot 2023-08-24 081819](https://github.com/S-ARVIND01/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/118707337/7fb450a2-f433-4860-be38-10322357cc6d)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

