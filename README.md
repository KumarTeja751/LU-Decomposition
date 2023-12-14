# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user 
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NARAMALA KUMARTEJA
RegisterNumber: 23003525
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NARAMALA KUMARTEJA
RegisterNumber: 23003525
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![image](https://github.com/KumarTeja751/LU-Decomposition/assets/144947756/18bbc19f-093d-4606-acde-b7583f5af7c3)
![image](https://github.com/KumarTeja751/LU-Decomposition/assets/144947756/96a485a8-507a-4cf0-9d6f-b02f70f9cbdc)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

