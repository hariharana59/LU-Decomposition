# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Hariharan A
RegisterNumber: 23012392

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

Program to find the LU Decomposition of a matrix.
Developed by: Hariharan A
RegisterNumber: 23012392

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
(i) To find the L and U matrix 
![image](https://github.com/hariharana59/LU-Decomposition/assets/144980130/26c6b45f-2b1b-45fa-9bda-3164a235a9b3)

(ii) To find the LU Decomposition of a matrix 
![image](https://github.com/hariharana59/LU-Decomposition/assets/144980130/11ba4a77-1def-478f-a5ea-eb2003359621)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

