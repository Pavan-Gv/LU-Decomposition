# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Give the condition to calculate LU Decomposition.
3. Assign any two values for input in runtime.
4. End the program.

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: G Venkata Pavan Kumar
RegisterNumber: 21005359
import numpy as np
from scipy.linalg import lu
A =np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
/*
Program to find the LU Decomposition of a matrix.
Developed by: G Venkata Pavan Kumar
RegisterNumber: 21005359
import numpy as np
from scipy.linalg import lu_factor, lu_solve

A=np.array(eval(input()))
B =np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

*/
```

## Output:
![lu decomposition](/pics/EX5li1.png)
![lu decomposition](/pics/EX5lu.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

