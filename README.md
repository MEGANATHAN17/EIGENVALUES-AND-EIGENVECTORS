# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.

### Step 2: 
Prepare the lists from each equations and assign in np.array()

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MEGANATHAN
#RegisterNumber:24900553
import numpy as np
a =[2,-3,0],[2,-5,0],[0,0,3]
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/1585b4d3-3176-4677-87d8-096c5eda4f5c)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

