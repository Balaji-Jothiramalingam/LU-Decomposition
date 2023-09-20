# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2. Import the numpy module and scipy.
3. Perform scipy.linalg.lu to find the pivot table, lower triangle and upper triangle matrix.
4. End the Program.

## Program:
(i) To find the L and U matrix
````
/*
Program to find the L and U matrix.
Developed by: BalajiJ
RegisterNumber: 212221243001
*/
import sys
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
````
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: BalajiJ
RegisterNumber:212221243001
*/

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

````
## Output:

![image](https://github.com/Balaji-Jothiramalingam/LU-Decomposition/assets/114234865/4199d341-3926-4dd0-8479-729e8ef70964)

![image](https://github.com/Balaji-Jothiramalingam/LU-Decomposition/assets/114234865/630e0328-ca90-49d4-8a27-0cdd90969c2a)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

