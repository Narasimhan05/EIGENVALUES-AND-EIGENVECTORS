# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation

### Step 2: 
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4: 
End the program

## Program:

```
import numpy as np
A = np.array([[4, 2],
              [2, 4]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```

## Output:
![alt text](<Screenshot 2024-04-10 215754.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
