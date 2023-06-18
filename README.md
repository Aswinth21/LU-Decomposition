# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu,lu_factor,lu_piv
3. Get input from the user as eval(input())
4. Use lu_factor and lu_solve to find LU decomposition
5. print L,U
6. print x

## Program:
(i) To find the L and U matrix
```python
#Program to find the L and U matrix.
#Developed by: ASWINTH T
#RegisterNumber: 212222230015
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
/*
Program to find the LU Decomposition of a matrix.
Developed by: ASWINTH T
RegisterNumber: 212222230015
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/Aswinth21/LU-Decomposition/assets/120236638/1ba645c0-538e-4b46-beef-b506fae9776d)<br>
![image](https://github.com/Aswinth21/LU-Decomposition/assets/120236638/e4912dd7-8b3e-4fdb-ad1d-b4fc80b48bab)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

