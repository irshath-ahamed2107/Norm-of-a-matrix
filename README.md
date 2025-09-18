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
# Register No:212224110025
# Developed By:Irshath Ahamed.N
```
## 1-Norm of a Matrix

```python
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```

# 2-Norm of a Matrix
```python
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))
```
# Infinity Norm of a Matrix
```python
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))
```


## Output:
### 1-Norm of a Matrix
<img width="1287" height="942" alt="Screenshot 2025-09-18 133704" src="https://github.com/user-attachments/assets/2207c5ae-b402-49ae-b78e-ac4743fe4335" />



### 2-Norm of a Matrix
<img width="1292" height="968" alt="Screenshot 2025-09-18 133727" src="https://github.com/user-attachments/assets/8c6ac8d5-5761-484e-9da3-1ea313a5e030" />




### Infinity Norm of a Matrix
<img width="1299" height="927" alt="Screenshot 2025-09-18 133753" src="https://github.com/user-attachments/assets/4918faa1-0235-4784-96f5-8898568b2d4e" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
