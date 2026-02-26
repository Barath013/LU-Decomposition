# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program

2.Import the necessary libraries(numpy,scipy.linalg)

3.Define the matrix using numpy

4.Use lu(),lu_solve(),lu_factor() to get the solutions

5.End the program

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: BARATH V
RegisterNumber: 212225240023
'''
import numpy as np
from scipy.linalg import lu
m = np.array(eval(input()))
p,l,u = lu(m)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: BARATH V
RegisterNumber: 212225240023
'''

# To print X matrix (solution to the equations)
import numpy as np
import scipy.linalg
m =np.array(eval(input()))
b = np.array(eval(input()))
p,lu = scipy.linalg.lu_factor(m)
ans = scipy.linalg.lu_solve((p,lu),b)
print(ans)
*/
```

## Output:



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

