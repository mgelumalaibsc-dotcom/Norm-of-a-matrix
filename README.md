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
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat =np.array(eval(input()))
ans =np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat =np.array(eval(input()))
ans =np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


```
## Output:
### 1-Norm of a Matrix
<img width="1196" height="215" alt="image" src="https://github.com/user-attachments/assets/1fdb61f2-328b-4b40-8e4a-c876ef91c14c" />


### 2-Norm of a Matrix
<img width="1196" height="263" alt="image" src="https://github.com/user-attachments/assets/1662a630-4df5-4ae6-892d-191e1a84dab3" />


### Infinity Norm of a Matrix
<img width="1196" height="219" alt="image" src="https://github.com/user-attachments/assets/2c4cdce1-d221-468a-80f5-cb2d7d7da19d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
