# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import the numpy module to use the built in function for calculation
### Step 2: 
Perpare the lists from linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
 # Program to find the eigen value and eigen vector.
 # Developed by:SANJAI S
 # Register Number:23013614
~~~
import numpy as np
a = np.array([[4,2],[2,4]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

~~~


## Output:
![Screenshot 2023-12-16 153230](https://github.com/Sanjaichitra/EIGENVALUES-AND-EIGENVECTORS/assets/144870518/ccb532f7-ff36-426a-995f-511bc3a38bc4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
