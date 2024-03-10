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
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)


````
## Output:

![b4](https://github.com/Balaji-Jothiramalingam/LU-Decomposition/assets/114234865/6723a80b-be78-43d8-82ac-f804f777e5f6)

![b5](https://github.com/Balaji-Jothiramalingam/LU-Decomposition/assets/114234865/5f53a641-5310-4f39-8709-4460e9bec003)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

