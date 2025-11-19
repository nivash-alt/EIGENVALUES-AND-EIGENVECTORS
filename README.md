# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
import numpy as np   
A = np.array([[4,2],[2,4]])   
values,vectors = np.linalg.eig(A)   
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")     

## Output:
<img width="1323" height="808" alt="Screenshot 2025-11-19 114345" src="https://github.com/user-attachments/assets/e433ddf8-fc41-4e54-9d8f-054d812f7d0e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
