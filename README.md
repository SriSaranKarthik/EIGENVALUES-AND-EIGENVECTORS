# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:K.SRISARAN KARTHIK
#RegisterNumber:212224230275
import numpy as np
a=[4,2],[2,4]
eig_values,eig_vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))
```

## Output:
![image](https://github.com/user-attachments/assets/c0fd6359-e5dc-49b3-9bb7-c6c28879cf0c)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
