# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import required libraries numpy and scipy.linalg.

Step 2:
Input the matrix/matrices using eval(input()).

Step 3:
Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

Step 4:
Print the results L and U matrices or solution X matrix.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: MANIKANDAN K
RegisterNumber: 212224230150

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: MANIKANDAN K
RegisterNumber: 212224230150

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
l,p=lu_factor(A)
s=lu_solve((l,p),B)
print(s)

```

## Output:
<img width="1220" height="957" alt="image" src="https://github.com/user-attachments/assets/58361fee-aed2-4950-bb0f-5c2e97fe110e" />
<img width="1231" height="875" alt="image" src="https://github.com/user-attachments/assets/5f36fb99-fdd1-473d-8af0-6db06f96435f" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

