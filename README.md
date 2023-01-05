# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the list for a matrix and assign in np.array() 
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Laakshit D
#RegisterNumber: 22000680
import numpy as np
a=np.array([[1,2,3],[3,6,9]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:
![output](/Screenshot%20from%202023-01-05%2019-08-44.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

