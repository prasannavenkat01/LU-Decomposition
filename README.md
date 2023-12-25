# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. From scipy.linalg import lu
2. Import numpy as np
3. Get the matrix value
4. Print the final result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Prasanna V 
RegisterNumber: 23006873
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by: Prasanna v
RegisterNumber: 23006873
'''

# To print X matrix (solution to the equations)
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

![Screenshot 2023-12-25 161256](https://github.com/prasannavenkat01/LU-Decomposition/assets/150702500/5d645ffa-1ce5-4ab4-8be7-56eef3b145e9)

![Screenshot 2023-12-25 161419](https://github.com/prasannavenkat01/LU-Decomposition/assets/150702500/5d39a983-9e94-4c2c-b441-fccfa4626c38)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

