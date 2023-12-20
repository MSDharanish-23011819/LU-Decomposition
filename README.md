# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2. Get the array input from the user.
3. Prepare the lists from the given matrix and assign in np.array().
4. Print thr L U matrix values. 

## Program
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: MS Dharanish
#RegisterNumber: 23011819
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
#Program to solve a matrix using LU decomposition.
#Developed by: MS Dharanish 
#RegisterNumber:23011819 


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
(i) To find the L and U matrix

![Screenshot 2023-12-20 194901](https://github.com/MSDharanish-23011819/LU-Decomposition/assets/147139454/039c89b4-da2b-42d5-8953-be1ba6e4fb1e)

(ii) To find the LU Decomposition of a matrix

![Screenshot 2023-12-20 195401](https://github.com/MSDharanish-23011819/LU-Decomposition/assets/147139454/f082eba8-471a-4af5-b329-fedda7aa522f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

