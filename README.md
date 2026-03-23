# Norm of a matrix
# NAME : SHREEJA R S
# REF.NO : 25017561

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
# Register No: 25017561
# Developed By: SHREEJA R S
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
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")




# Infinity Norm of a Matrix


import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm)



```
## Output:
### 1-Norm of a Matrix
![Screenshot_23-3-2026_235054_lms2 ai saveetha in](https://github.com/user-attachments/assets/737e73aa-ee62-43fa-bb43-c25366969746)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot_23-3-2026_235116_lms2 ai saveetha in](https://github.com/user-attachments/assets/e52ba74e-4d38-47bb-bfa2-2a23d621437e)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot_23-3-2026_235131_lms2 ai saveetha in](https://github.com/user-attachments/assets/3a02f20a-a896-42db-b4f8-d26f193f2dea)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
