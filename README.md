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
# Register No:24901141
# Developed By:paulshervin.p
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,1)
print(norm)
# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,2)
print(f"{norm:.2f}")

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")




```
## Output:
### 1-Norm of a Matrix
<br>![output](image.png)
<br>
<br>

### 2-Norm of a Matrix
<br>![output](image-1.png)
<br>
<br>

### Infinity Norm of a Matrix
<br>
<br>!![Screenshot 2024-12-13 182246](https://github.com/user-attachments/assets/b2d4be57-f864-42a2-acb5-4a85aed6ad01)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
