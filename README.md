# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: 
End the Program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])

inverse = np.linalg.inv(A)

print(inverse)
```
## Output:

<img width="1027" height="417" alt="image" src="https://github.com/user-attachments/assets/cc022680-0f6f-4bc0-8e90-c0fae5dafb81" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

