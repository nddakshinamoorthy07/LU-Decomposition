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
 Developed by: DAKSHINA MOOTHY N D
RegisterNumber: 24900826
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu, piv), b)
print(x)
```
## Output:
![alt text](<Screenshot 2024-12-05 162252.png>)
![alt text](<Screenshot 2024-12-05 162307.png>)
![alt text](<Screenshot 2024-12-05 162321.png>)
![alt text](<Screenshot 2024-12-05 162334.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

