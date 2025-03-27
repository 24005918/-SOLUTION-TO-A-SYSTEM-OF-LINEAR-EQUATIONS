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

#Program to find the solution for the given linear equations.
#Developed by:  SANTHOSH V
#RegisterNumber: 212224230252
import numpy as np
A = np.array([[1, 3], [2, 5]])
b = np.array([5, -3])
solution = np.linalg.solve(A, b)
print(np.array(solution))  


## Output:
![{BC4889CB-E666-4810-8042-84F2B213BAB8}](https://github.com/user-attachments/assets/ac362618-0fed-4b72-a7c2-1a430e50b6a0)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

