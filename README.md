# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
~~~
  import numpy as np
  matrix = np.array([
      [4, 2],
      [2, 4]
  ])
~~~
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

## Output:
![Screenshot 2025-01-08 210314](https://github.com/user-attachments/assets/b64631e2-7601-4491-9796-0c94d81ada42)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
