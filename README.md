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
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv(), we can find the inverse of the given matrix
### Step 4: 
print the result
## Program:
```

#Program to find the inverse of a matrix.
#Developed by:Ezhil Nilavan E
#RegisterNumber:26018188
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
r=np.linalg.inv(a)
print(r)
```

## Output:
<img width="398" height="161" alt="Screenshot From 2026-10-16 09-00-50" src="https://github.com/user-attachments/assets/bd774848-b338-4cbb-9cfc-57a7b323586b" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

