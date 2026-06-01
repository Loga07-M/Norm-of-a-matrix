# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
	
### ALGORITHM 1: To Find the 1-Norm of a Matrix

1. Start the program and import the required library `numpy`.
2. Get the input matrix using `eval()`.
3. Find the 1-norm of the matrix using `np.linalg.norm(matrix, 1)`.
4. Display the norm in two decimal places.
5. End the program.


### ALGORITHM 2: To Find the 2-Norm of a Matrix

1. Start the program and import the required library `numpy`.
2. Get the input matrix using `eval()`.
3. Find the 2-norm of the matrix using `np.linalg.norm(matrix, 2)`.
4. Display the norm in two decimal places.
5. End the program.


### ALGORITHM 3: To Find the Infinity Norm of a Matrix

1. Start the program and import the required library `numpy`.
2. Get the input matrix using `eval()`.
3. Find the infinity norm of the matrix using `np.linalg.norm(matrix, np.inf)`.
4. Display the norm in two decimal places.
5. End the program.


## Program:
```Python
''' Program to find the 1-Norm of a matrix and display the results in two decimal places
Developed by:LOGA SRI M
Register number:212225230153
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))




# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np 
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
    



```
## Output:
### 1-Norm of a Matrix
<img width="1253" height="320" alt="image" src="https://github.com/user-attachments/assets/999588b2-31f6-475f-9ba5-4e1e24a739e1" />

### 2-Norm of a Matrix
<img width="1255" height="372" alt="image" src="https://github.com/user-attachments/assets/c17bd400-6fc2-4500-ad99-c2e31a1c607d" />


### Infinity Norm of a Matrix
<img width="1277" height="350" alt="image" src="https://github.com/user-attachments/assets/413b034f-dad7-4a61-85b5-762e6e56dd4d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
