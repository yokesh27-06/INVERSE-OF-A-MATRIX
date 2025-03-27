# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library.
### Step 2: Define the given square matrix A as a NumPy array.
### Step 3: Compute the inverse of matrix A using np.linalg.inv(A).
### Step 4: Store the result in the variable result.
### Step 5: Print the inverse matrix stored in result.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: YOKESH H 
#RegisterNumber:212224230312
import numpy as np
matrix = np.array([[1, 0, 3],
                   [-1, 2, -2],
                   [2, 3, -1]])
inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
```
## Output:
![alt text](<Screenshot 2025-03-27 145031.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

