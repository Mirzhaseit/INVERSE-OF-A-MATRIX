# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : The matrix a is defined as a NumPy array.
### Step 2:  np.linalg.inv(a) computes the inverse if the matrix is invertible.
### Step 3: If the matrix is singular (determinant is zero), the code raises a LinAlgError.
### Step 4: run the program

## Program:
```
import numpy as np
a=np.array([[6,2,3],[3,1,1,],[10,3,4]])
b=np.linalg.inv(a)
print(b)
```
## Output:

![image](https://github.com/user-attachments/assets/710d738b-fe08-4fb9-a620-ba1c88062970)

## Result:
Thus the inverse of given matrix is successfully solved using python program

