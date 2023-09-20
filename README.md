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

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: BalajiJ
RegisterNumber:212221243001
*/
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

````
## Output:

![image](https://github.com/Balaji-Jothiramalingam/LU-Decomposition/assets/114234865/017ad19d-6e1e-46ee-86cc-3af5caf52d19)

![image](https://github.com/Balaji-Jothiramalingam/LU-Decomposition/assets/114234865/ad40bbe0-0552-4f7e-bfce-95e3d81989e1)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

