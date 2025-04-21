# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
 
## Program:
```Python
# Register No: 212224230225
# Developed By: RAVIPRASATH K
```
# 1-Norm of a Matrix
```
'''
Program to find norm of a matrix. 
Developed by: RAVIPRASATH K
RegisterNumber: 212224230225 
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print(f"{ans:.2f}")
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: RAVIPRASATH K
RegisterNumber: 212224230225
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print(f"{ans:.2f}")
 ```
# Infinity Norm of a Matrix
```
'''
Developed by: RAVIPRASATH K
RegisterNumber: 212224230225 
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print(f"{ans:.2f}")
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/2f4f356f-cb0b-4f66-9ada-552a39fee44e)

### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/5f9bda8d-99bf-41cc-8a97-0c07eb1fe956)

### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/308b1253-5a3b-4570-aa49-ed5f3a391a8c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
