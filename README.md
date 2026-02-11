# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and scipy.linalg.lu
2. Input the square matrix 
𝐴

3. Perform LU decomposition: P, L, U = lu(A)
4. Print 𝐿 L and 𝑈 U matrices

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: VISHNUPRIYA E
RegisterNumber: 212225230308
'''
import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U = lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: VISHNUPRIYA E
RegisterNumber:212225230308 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix = np.array(eval(input()))
constant = np.array(eval(input()))
piv,lu=lu_factor(matrix)
result = lu_solve((piv,lu),constant)
print(result)

```

## Output:
![alt text](<Screenshot 2026-02-11 214118.png>)
![alt text](<Screenshot 2026-02-11 214201.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

