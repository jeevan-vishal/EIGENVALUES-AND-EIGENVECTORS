# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np

### Step 2: 
get the inputs as array

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
now, print the step 3

## Program:
```
import numpy as np
a=np.array([[-2,2,-3],
           [2,1,-6],
           [-1,-2,0]])
eigv,eigvector=np.linalg.eig(a)
print("Eigen values are",eigv,"and Eigen Vectors are",eigvector)
```

## Output:
![Screenshot 2025-04-23 112649](https://github.com/user-attachments/assets/b0733971-0eff-4818-86e4-635fc82b6461)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
