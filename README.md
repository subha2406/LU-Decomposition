# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
step1:
Define the package as scipy.linalg import lu.
step2:
Get input from user and print L and U matrix by 'Print' . 
step3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variance 
step4:
Print the variable 'X' 
```
## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: subha shree U
RegisterNumber:2305002025

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Subha shree U
RegisterNumber: 2305002025

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://github.com/subha2406/LU-Decomposition/assets/155226504/813110ce-b03c-45e4-b589-8b525c081cfb)
![image](https://github.com/subha2406/LU-Decomposition/assets/155226504/b393a374-4251-4c3e-9234-36604025222a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

