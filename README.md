# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
   
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Karthik J
RegisterNumber: 212225040176
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Karthik J
RegisterNumber: 212225040176 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivol=lu_factor(A)
x=lu_solve((lu,pivol),B)
print(x)
```

## Output:

<img width="1441" height="775" alt="Screenshot 2026-02-07 082254" src="https://github.com/user-attachments/assets/3e25ec91-a96a-43ba-9448-9dae812505cc" />
<img width="1447" height="585" alt="Screenshot 2026-02-07 082311" src="https://github.com/user-attachments/assets/8acb4880-21a8-4304-9e93-ae0dc2ec096b" />

<img width="1439" height="731" alt="Screenshot 2026-02-07 082330" src="https://github.com/user-attachments/assets/12b70f0d-9586-4f00-a0b0-419aad5ac2e1" />
<img width="1446" height="364" alt="Screenshot 2026-02-07 082349" src="https://github.com/user-attachments/assets/8cb37108-ab3a-4302-90ad-16b09a9f46cc" />

## Result:
Thus the solutions for the  LU Decomposition  are successfully solved using python program

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

