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
# Register No:212225240086
# Developed By: MOHAMED SHIAF N
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

<img width="1080" height="815" alt="Screenshot 2026-03-10 202014" src="https://github.com/user-attachments/assets/66cd906e-0546-45da-8c56-1da8833ea235" />


### 2-Norm of a Matrix

 <img width="866" height="861" alt="Screenshot 2026-03-10 202026" src="https://github.com/user-attachments/assets/6805e88c-2015-4616-a784-ac5cfa9a4529" />


### Infinity Norm of a Matrix

<img width="901" height="811" alt="Screenshot 2026-03-10 202046" src="https://github.com/user-attachments/assets/a02e19aa-00ed-49a7-b08c-66b5402f4817" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
