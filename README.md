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
# Register No: 212224240046
# Developed By: GOWTHAM C
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"] ="1"

import numpy as np 
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,1) 
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = '1'
import numpy as np 
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,2) 
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf) 
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<br> <img width="831" height="948" alt="image" src="https://github.com/user-attachments/assets/bbaaa685-3482-4360-85e6-4f58abda55c6" />

<br>
<br>

### 2-Norm of a Matrix
<br> <img width="815" height="943" alt="image" src="https://github.com/user-attachments/assets/b608e247-b74b-4ea0-84ee-631427515a26" />

<br>
<br>

### Infinity Norm of a Matrix
<br> <img width="745" height="818" alt="image" src="https://github.com/user-attachments/assets/7e4c9146-1594-4d03-9c6f-f4cadd7737d6" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
