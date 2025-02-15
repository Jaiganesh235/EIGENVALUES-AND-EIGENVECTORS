# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the library numpy using the import command. 
### Step 2: 
Assigning a matrix to a variable.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and eigen vectors of the matrix and end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: S.Jaiganesh
#RegisterNumber: 212222240037

import numpy as np
from numpy.linalg import eig
a=np.array([[2,2],[1,3]])
w,v=eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(w,v))
```

## Output:
![image](https://user-images.githubusercontent.com/118657189/227957629-204ff32e-2cfa-44eb-9c4d-72b9bd2859fc.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
