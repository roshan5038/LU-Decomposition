# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Roshan V 
RegisterNumber: 212225240124
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
from scipy.linalg import lu

A = eval(input())

A = np.array(A, dtype=float)

P, L, U = lu(A)

print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Roshan V
RegisterNumber: 212225240124
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

A = np.array(eval(input()), dtype=float)
B = np.array(eval(input()), dtype=float)

X = np.linalg.solve(A, B)

print(X)
*/
```

## Output:
<img width="861" height="842" alt="image" src="https://github.com/user-attachments/assets/84bb45ff-b812-4437-8b22-f614b99f8f60" />
<img width="1364" height="726" alt="image" src="https://github.com/user-attachments/assets/c86bdba2-4a75-459f-8298-2d5eaa7ac230" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

