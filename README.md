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
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-10 190656](https://github.com/user-attachments/assets/1061da13-e794-4e72-99e2-2fde1dbda83a)


### 2-Norm of a Matrix>
![Screenshot 2024-12-10 190718](https://github.com/user-attachments/assets/48045901-3435-44ad-833c-5ad1b8e5b13b)

### Infinity Norm of a Matrix
![Screenshot 2024-12-10 190732](https://github.com/user-attachments/assets/82ef57e7-7be9-4bf9-b1d6-ebad32394e3c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
