# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the necessary library, numpy, for matrix operations. 
### Step 2:Define the given matrix using the numpy.array() method.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors using the print() function.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: G SANJAY
#RegisterNumber:212224230243
```
```
import numpy as np
A = np.array([[2, 2], [1, 3]])
eig_values, eig_vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values, eig_vectors))
```
## Output:
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/270ef190-5b64-4640-ade5-c5ccab3e5019" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
