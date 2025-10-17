# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1.Input the matrix

2.Import numpy and lu from scipy.linalg

3.Find L,U

4.Find the LU decomposition  
 
## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.

Developed by: M AMRITA

RegisterNumber:25011865

import numpy as np

from scipy.linalg import lu

a = np.array(eval(input()))

p,l,u=lu(a)

print(l)

print(u)

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.

Developed by: M AMRITA

RegisterNumber: 25011865

import numpy as np

from scipy.linalg import lu_factor, lu_solve

a = np.array(eval(input()))

b = np.array(eval(input()))

lu,pivot=lu_factor(a)

x = lu_solve((lu,pivot), b)

print(x)

```

## Output:

i)

<img width="624" height="222" alt="image" src="https://github.com/user-attachments/assets/bce2efea-4076-442e-8fa1-7fc7322a73d5" />

ii)

<img width="613" height="136" alt="image" src="https://github.com/user-attachments/assets/ea9b2645-7325-42e0-91bd-d75ba3473928" />

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

