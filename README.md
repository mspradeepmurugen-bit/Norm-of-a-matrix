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
# Register No:212225220071
# Developed By:PRADEEP.M
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


```
# 2-Norm of a Matrix

import numpy as np

# Type your code here
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

```
# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```




## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1269" height="846" alt="Screenshot 2026-03-18 141420" src="https://github.com/user-attachments/assets/021c44b4-053e-49b8-b7e7-1e6b3c435d89" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1260" height="833" alt="Screenshot 2026-03-18 141437" src="https://github.com/user-attachments/assets/ec1e927f-5f59-48a4-ae91-8901ad7718cf" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1279" height="699" alt="Screenshot 2026-03-18 141452" src="https://github.com/user-attachments/assets/5cf7ec60-16c8-418e-a467-0978fdb564f1" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
