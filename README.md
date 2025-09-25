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
# Register No: RAGASUDHA R
# Developed By:212224230215

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix

<img width="1229" height="930" alt="m1" src="https://github.com/user-attachments/assets/e77525ef-8d68-40e0-85fa-8e5cd734fd50" />

### 2-Norm of a Matrix
<img width="1218" height="946" alt="m2" src="https://github.com/user-attachments/assets/19b9af81-bb16-43e7-807b-837087385a38" />


### Infinity Norm of a Matrix

<img width="1187" height="905" alt="m3" src="https://github.com/user-attachments/assets/7b564c19-094c-455c-99dd-5d1b4f2bdc4c" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
