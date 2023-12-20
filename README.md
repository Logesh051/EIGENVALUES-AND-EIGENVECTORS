# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculations

### Step 2:
Prepare the list from each eigenvalues,eigenvectors and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program: 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Logesh.N.A
#RegisterNumber: 23012242
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:

![Screenshot 2023-12-20 135158](https://github.com/Logesh051/EIGENVALUES-AND-EIGENVECTORS/assets/144979188/bfe03fad-9343-42ee-85b4-3a371ab517b9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
