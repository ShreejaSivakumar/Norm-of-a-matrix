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
	Here’s a **single concise algorithm outline** that covers all three matrix norm codes you shared:


1. **Start the program.**  
2. **Import NumPy and set environment variables.**  
3. **Input the matrix \(A\).**  
4. **Compute matrix norm using `np.linalg.norm`:**  
   - Infinity norm (\(\|A\|_\infty\))  
   - Euclidean norm (\(\|A\|_2\))  
   - One norm (\(\|A\|_1\))  
5. **Format and print the result.**  
6. **End the program.**

1. Import `os` and `numpy`.  
2. Set `OPENBLAS_NUM_THREADS = "1"`.  
3. Read matrix input → convert to NumPy array.  
4. Compute norm using `np.linalg.norm(A, p)` where  
   - `p = 1` → 1-norm
   -  - `p = 2` → 2-norm 
   - - `p = np.inf` → ∞-norm 
5. Format result if needed.  
6. Print the norm.


## Program:
```
Python
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

![Screenshot_23-3-2026_235054_lms2 ai saveetha in](https://github.com/user-attachments/assets/570a55fe-abbf-47ee-a6ac-afda1313a1ab)

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

