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
![7thai1](https://github.com/user-attachments/assets/ca790c0c-7ff4-476b-83c1-b60a532c4d0e)


### 2-Norm of a Matrix
![7thai2](https://github.com/user-attachments/assets/c7e92950-5f1a-48bf-b09a-835057c438eb)


### Infinity Norm of a Matrix
![7thai3](https://github.com/user-attachments/assets/50a8e464-1cef-4554-804c-04cb5796173b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
