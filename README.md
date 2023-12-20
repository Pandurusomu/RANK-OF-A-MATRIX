# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists of elements in each row in matrix and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: Panduru somu
#RegisterNumber: 23005083 

import numpy as np

mat = np.array([[1,2,3],[3,6,9]])
rank = np.linalg.matrix_rank(mat)
print(rank)
~~~
## Output:
![Screenshot 2023-12-20 174847](https://github.com/Pandurusomu/RANK-OF-A-MATRIX/assets/148988619/eabc89e0-db8e-4237-a581-2e7f66da9164)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

