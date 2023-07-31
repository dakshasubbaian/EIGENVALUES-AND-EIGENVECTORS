# EIGENVALUES-AND-EIGENVECTORS
## AIM:
To write a python program to find the Eigenvalues and Eigen Vectors
## EQUIPMENTS REQUIRED:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## PROGRAM:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Daksha Subbaian
#RegisterNumber: 23003584
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## OUTPUT:
![output](/exp04output.png)
## RESULT:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
