# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy module
### Step 2: 
input the given array in arr
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the eigen vectors and the eigen values
## Program:
```#Program to find the eigen values and eigen vectors.
#Developed by: Karthick Raja K
#RegisterNumber:23006120
import numpy as np
arr=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(arr)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![output](/Screenshot%202023-07-31%20114905.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
