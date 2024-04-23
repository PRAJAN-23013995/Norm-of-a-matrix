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
# Register No:212223240121
# Developed By:PRAJAN P
# 1-Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")

# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")

# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 113128](https://github.com/PRAJAN-23013995/Norm-of-a-matrix/assets/150313345/2cf3237d-88ca-421e-9577-1ba8776f2512)

### 2-Norm of a Matrix
![Screenshot 2024-04-23 113145](https://github.com/PRAJAN-23013995/Norm-of-a-matrix/assets/150313345/1cfe42bd-da95-40cc-b243-671c2d15b3be)

### Infinity Norm of a Matrix
![Screenshot 2024-04-23 113158](https://github.com/PRAJAN-23013995/Norm-of-a-matrix/assets/150313345/4065dd96-cfe4-447f-b810-2a570df55793)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
