# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module to use built-in linear algebra functions.
### Step 2: Create the matrix using np.array() and store it in a variable A.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors to display the result.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHRIHARI M
#RegisterNumber:212225230265
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
matrix = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eig_values, eig_vectors = np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values, eig_vectors))
```
## Output:
<img width="1317" height="125" alt="Screenshot 2026-05-07 111656" src="https://github.com/user-attachments/assets/07be169f-dbf9-4e54-a2f0-bc2bbcea4bf1" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
