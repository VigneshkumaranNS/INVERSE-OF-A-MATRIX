# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in
functions for calculation
### Step 2: 
Prepare the lists from each linear equations and 
assign in np.array()
### Step 3:
using the np.linalg.inv(),we can find the inverse of
the given matrix.
### Step 4:
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Vignesh Kumaran N.S
#RegisterNumber:22008928
import numpy as np
A = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
B = np.linalg.inv(A)
print(B)
```
## Output:
![input12](inverse.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

