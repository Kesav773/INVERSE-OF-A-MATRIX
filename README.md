# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the build-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.inv(),we can find the solution

Step 4:
End the program

## Program:
#Program to find the inverse of a matrix.
#Developed by:Kesav KM
#RegisterNumber:212224110031
import numpy as np
A = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])
inverse_A = np.linalg.inv(A)
print(inverse_A)
## Output:
![Screenshot 2025-03-27 204233](https://github.com/user-attachments/assets/bc4819a8-1de0-400b-aa02-cb26224b9596)

## Result:
Thus the inverse of given matrix is successfully solved using python program

