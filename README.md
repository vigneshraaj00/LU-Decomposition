# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.first use the import 
2.second use the numpy operatore
3.thrid i use the print statment 
4.i got the output


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix. 
*/
```
Program to find L and U matrix using LU decomposition.
Developed by:vignesh raaj s
RegisterNumber:23005346
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:vignesh raaj s
RegisterNumber:23005346
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np 
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)

/*
Program to find the LU Decomposition of a matrix.
Developed by: vignesh raaj s
RegisterNumber: 23005346
*/
```
## Output:
![Screenshot 2023-12-27 113821](https://github.com/vigneshraaj00/LU-Decomposition/assets/138849113/4a073ec9-ef59-4460-9458-d12fe6259702)
![Screenshot 2023-12-27 113836](https://github.com/vigneshraaj00/LU-Decomposition/assets/138849113/7ee85f65-4741-4c5f-a8e3-ffae2c51c276)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

