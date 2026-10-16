# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equation and assign in np.array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:end the program 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: R SARAN
#RegisterNumber: 26004406
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
r=np.linalg.matrix_rank(a)
print(r)
```
## Output:
<img width="1315" height="230" alt="image" src="https://github.com/user-attachments/assets/80ddec40-6220-4180-8b1b-0676d6f047af" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

