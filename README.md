# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy 
2. use np.array for matrix solving
3. assign the value
4.End the program 

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by:KAMESH 
RegisterNumber: 2406280
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: KAMESH 
RegisterNumber: 2406280
*/
```
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

b=np.array(eval(input()))

lu, piv=lu_factor(A)

X=lu_solve((lu,piv),b)

print(X)

## Output:

![Screenshot 2024-12-03 101257](https://github.com/user-attachments/assets/12c58f8f-aa03-4de2-9f68-3b61819260c5)


![Screenshot 2024-12-03 101654](https://github.com/user-attachments/assets/6dc063ca-0e22-45e0-a297-721f42122e96)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

