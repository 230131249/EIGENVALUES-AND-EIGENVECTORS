# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import thePrepare the lists from each equations and assign in np.array()
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
Eigen_Values,Eigen_Vectors=np.linalg.eig(A)
print("Eigen values are",Eigen_Values,"and Eigen Vectors are",Eigen_Vectors)
## Output:
![image](https://github.com/230131249/EIGENVALUES-AND-EIGENVECTORS/assets/150232701/94d71ee7-f238-4f96-9b4c-0ad1dee9c22d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
