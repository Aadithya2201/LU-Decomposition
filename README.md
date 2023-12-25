# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for L and U Matrix
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu
3. Enter the lists from each linear equations and assign in np.array()
4. using lu() and store it in three variables
5. print the L and U Matrix
6. End the program

## Algorithm for LU Decomposition
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu_factor,lu_solve
3. Enter the lists from each linear equations and assign in np.array()
4. Enter the lists from each linear equations and assign in np.array()
5. using lu_factor() and store it in two variables
6. using lu_solve(),we can find L and U matrix
7. End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Aadithya.R
RegisterNumber: 23006361
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Aadithya.R
RegisterNumber: 23006361
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,plv=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
```

## Output:
![Screenshot 2023-12-25 132913](https://github.com/Aadithya2201/LU-Decomposition/assets/145917810/14180515-49f6-4648-8a04-1f776f54e38a)

![Screenshot 2023-12-25 133417](https://github.com/Aadithya2201/LU-Decomposition/assets/145917810/fd89fda8-5bb6-4b52-8700-74c044b2d6fc)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

