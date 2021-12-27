# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import numpy library using import statement.

Step 2:
From scipy package import lu().

Step 3:
Get inputs from the user and pass it an array.

Step 4:
Get P,L,U matrix using lu()

Step 5:
Print L and U matrix


### Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Paarkavy B
RegisterNumber: 21500424
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
#import scipy
A = np.array(eval(input()))
P,L,U =lu(A)
#P,L,U = scipy.linalg.lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Paarkavy B 
RegisterNumber: 21500424
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![lu decomposition](./LU.png)
![lu decomposition](./LUDE.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

