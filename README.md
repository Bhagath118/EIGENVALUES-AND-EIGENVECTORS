# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program
### Step 2: 
Deffine the matrix
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: A.Bhagathkrishna
#RegisterNumber:23002963
import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![output]![eigen](https://github.com/Bhagath118/EIGENVALUES-AND-EIGENVECTORS/assets/147473779/39e81a99-93e8-4f51-94fa-40af3cdda4fd)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
