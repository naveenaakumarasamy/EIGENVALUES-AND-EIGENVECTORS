# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy
### Step 2: 
Assign values for the array
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and vectors

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Naveenaa A.k
#RegisterNumber:22003091
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```

## Output:
![eigen values and vectors](https://user-images.githubusercontent.com/113497406/191307165-214135c3-9edf-4327-b2f7-a8b4594e5507.png)

## Result:
The eigen values and eigen vectors are executed successfully
