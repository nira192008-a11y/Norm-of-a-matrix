# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm and 1-norm ,infinite of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:26006895
# Developed By: NIRANJAN P
# 1-Norm of a Matrix

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

Norm_of_matrix="{:.2f}".format(ans)

print(Norm_of_matrix)

# 2-Norm of a Matrix

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

Norm_of_matrix="{:.2f}".format(ans)

print(Norm_of_matrix)





# Infinity Norm of a Matrix

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,np.inf)

print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix
<img width="697" height="705" alt="image" src="https://github.com/user-attachments/assets/349f0f32-edb4-4c7d-8464-035863d1739a" />


### 2-Norm of a Matrix
<img width="820" height="861" alt="image" src="https://github.com/user-attachments/assets/6fa63e52-9474-45c8-a91b-f704c4514ced" />


### Infinity Norm of a Matrix
<img width="878" height="771" alt="image" src="https://github.com/user-attachments/assets/713b6335-631d-47f4-a1c3-e538604d20c4" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
