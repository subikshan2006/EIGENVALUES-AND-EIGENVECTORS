# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : start the program
### Step 2: import numpy as np
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end ofa program

## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
b,c=np.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
```

## Output:
![Screenshot 2023-11-26 161521](https://github.com/subikshan2006/EIGENVALUES-AND-EIGENVECTORS/assets/139841805/50a5e4e0-a74e-46e4-a5ae-997db111c332)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
