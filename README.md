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
```
# Register No: 212223100007
# Developed By: T. Gayathri

## 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

## 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

## Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-09 114113](https://github.com/gayumee/Norm-of-a-matrix/assets/149037327/019979cb-ba56-4bb9-b782-bd2f90e7eed5)

### 2-Norm of a Matrix
![image](https://github.com/gayumee/Norm-of-a-matrix/assets/149037327/b2e886af-5667-4bec-a6a0-74f8a7f3b3b2)

### Infinity Norm of a Matrix
![Screenshot 2024-05-09 114113](https://github.com/gayumee/Norm-of-a-matrix/assets/149037327/a98acda2-3f99-4b10-80f4-25530ff4d594)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
