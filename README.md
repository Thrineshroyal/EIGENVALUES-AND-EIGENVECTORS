# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  
import the numpy modulo to use the built-in functions for calculation
### Step 2: 
get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Thrinesh Royal.T
#RegisterNumber:23004810
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Thrineshroyal/EIGENVALUES-AND-EIGENVECTORS/assets/145741928/aaacbed2-256d-4d1b-8fec-31d6ff531530)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
