# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

###Step 1: Import the NumPy library using import numpy as np.

###Step 2: Read or define the matrix elements and create the matrix using np.array().

###Step 3: Use the np.linalg.eig() function to obtain the Eigenvalues and Eigenvectors of the given matrix.

###Step 4: Display the Eigenvalues and Eigenvectors as output.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:dhanush rajan.t
#RegisterNumber: 212225230052
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array([
    [4, 2],
    [2, 4]
])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)



```


## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/596149fd-123e-4cba-8353-54de01074fa7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
