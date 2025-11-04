# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm 1:
1. Start and import the NumPy library using import numpy as np.
2. Input the matrix elements from the user using mat = np.array(eval(input())).
3. Compute the 1-Norm of the matrix using ans = np.linalg.norm(mat, 1).
4. Format the result to two decimal places using Norm_of_matrix = "{:.2f}".format(ans).
5. Display the formatted norm value using print(Norm_of_matrix) and Stop.
## Algorithm2:

1. Start and import the NumPy library using import numpy as np.
2. Input the matrix elements from the user using mat = np.array(eval(input())).
3.Compute the 2-norm of the matrix using ans = np.linalg.norm(mat, 2) — this gives the largest singular value (spectral norm).
4. Format the result to two decimal places using Norm_of_matrix = "{:.2f}".format(ans).
5. Display the formatted norm value using print(Norm_of_matrix) and Stop.

## Algorithm 3:
1. Start and import the NumPy library using import numpy as np.
2. Input the matrix elements from the user using mat = np.array(eval(input())).
3. Compute the infinity norm using ans = np.linalg.norm(mat, np.inf) — this finds the maximum absolute row sum of the matrix.
4. Format the result to two decimal places using Norm_of_matrix = "{:.2f}".format(ans).
5. Display the formatted norm value using print(Norm_of_matrix) and Stop.
    
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

![output](Screenshot%202025-09-25%20151243.png)

### 2-Norm of a Matrix
![output](Screenshot%202025-09-25%20151327.png)

### Infinity Norm of a Matrix

![output](Screenshot%202025-10-18%20141658.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
