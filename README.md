# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Santhose Arockiaraj J
#RegisterNumber: 212224230248

import numpy as np

A=np.array([
            [2,2],
            [1,3]
           ])
Value,Vector=np.linalg.eig(A)
print("Eigen values are",Value,"and Eigen Vectors are",Vector)
```

## Output:

<img width="829" height="731" alt="image" src="https://github.com/user-attachments/assets/31f431cc-496b-4cf7-beb8-0c33cf4d02db" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
