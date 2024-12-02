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


## Output:
### 1-Norm of a Matrix
<br>
<br>
![Screenshot 2024-12-01 201151](https://github.com/user-attachments/assets/9f21128f-c014-4e5f-b6ec-546985991345)
<br>

### 2-Norm of a Matrix
<br>
<br>
![Screenshot 2024-12-01 201243](https://github.com/user-attachments/assets/ece4de0c-b5ff-4402-8599-efbf8fd85797)
<br>

### Infinity Norm of a Matrix
<br>
<br>
![Screenshot 2024-12-01 201327](https://github.com/user-attachments/assets/1f037498-46cc-477f-be6c-c09521e35301)
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
