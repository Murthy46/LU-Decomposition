# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Sundaramurthy M
RegisterNumber:212222233006

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Sundaramurthy M 
RegisterNumber:212222233006

 # To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
<img width="1440" alt="Screenshot 2023-11-15 at 9 51 44 PM" src="https://github.com/Murthy46/LU-Decomposition/assets/145112768/ca239979-4f17-458d-9a4b-f930c67f4e0a">

<img width="1440" alt="Screenshot 2023-11-15 at 9 54 48 PM" src="https://github.com/Murthy46/LU-Decomposition/assets/145112768/fdbb2dcc-3bca-467a-9708-09e7ccf0cfa8">


![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

