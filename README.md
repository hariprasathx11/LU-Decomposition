# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program and import the required library(numpy)
2. initialize the matrix for which the lu decomposituion needs to be found
3. apply LU decomposition
4. Display the result
## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: S.Hariprasath
RegisterNumber: 25017723
'''
from scipy.linalg import lu
import numpy as np
A=np.array(eval(input()),dtype=float)
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
from scipy.linalg import lu_factor,lu_solve
import numpy as np
A=np.array(eval(input()),dtype=float)
B=np.array(eval(input()),dtype=float)
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

## Output:
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/9ff330d1-4cc9-494b-bfd8-9f81486848a8" />
<img width="1920" height="1080" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/6bf74026-8ed8-43ab-970d-b6e15ea6a002" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

