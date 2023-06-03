# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step1 :
we have imported numpy which is needed.

Step 2:
we have created a matrix using np.array with different values in it.

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
finally,print the values of the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: p.v.abishek
#RegisterNumber:212222230003
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```

## Output:
![Screenshot 2023-06-03 124153](https://github.com/pvabishek/EIGENVALUES-AND-EIGENVECTORS/assets/119405626/a69b8d30-d854-4e27-9bb8-bde1e21509b8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
