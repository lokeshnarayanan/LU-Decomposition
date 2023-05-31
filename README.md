# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy package as np

2.From scipy package import lu

3.Get input from the user

4.Print result 

## Program:
# (i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Lokesh N
RegisterNumber: 212222100023
*/
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)

```
# (ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Lokesh N
RegisterNumber: 212222100023
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:
# (i) To find the L and U matrix
![image](https://github.com/lokeshnarayanan/LU-Decomposition/assets/119393019/764d9f82-877a-4a98-8b44-8f74b1c63bd6)

# (ii) To find the LU Decomposition of a matrix
![image](https://github.com/lokeshnarayanan/LU-Decomposition/assets/119393019/b9a93755-448e-4fd4-8770-84c4d5b9f282)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

