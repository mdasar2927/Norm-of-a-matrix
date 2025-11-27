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
```
# Register No:25005844
# Developed By:MOHAMED ASARUDEEN A
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)


```
## Output:
### 1-Norm of a Matrix
<img width="1435" height="879" alt="Screenshot 2025-11-27 102412" src="https://github.com/user-attachments/assets/4e61fb84-3f1f-404e-95ae-e07b9d7281c5" />


### 2-Norm of a Matrix
<img width="1404" height="882" alt="Screenshot 2025-11-27 102431" src="https://github.com/user-attachments/assets/885ccccf-a449-436b-96fb-ed1a14d89f09" />


### Infinity Norm of a Matrix
<img width="1460" height="860" alt="Screenshot 2025-11-27 102443" src="https://github.com/user-attachments/assets/47629114-fb8a-45df-afeb-d1dda98f1e6c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
