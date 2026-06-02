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
## Developed by:Shunmathi S S
## Reg.No:212225040412
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix
## Developed by:Shunmathi S S
## Reg.No:212225040412
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
<img width="931" height="522" alt="Screenshot 2026-06-02 113849" src="https://github.com/user-attachments/assets/6e1552a2-5486-4b03-adf6-0d2135e8d8b6" />
<img width="704" height="332" alt="Screenshot 2026-06-02 113856" src="https://github.com/user-attachments/assets/d47441d2-41a6-4cfc-8892-b74e6b2e0c8b" />


### 2-Norm of a Matrix
<img width="1198" height="747" alt="Screenshot 2026-06-02 113907" src="https://github.com/user-attachments/assets/3a888cee-d40c-4cc4-8999-e765f46c961f" />
<img width="1178" height="328" alt="Screenshot 2026-06-02 113916" src="https://github.com/user-attachments/assets/098c615a-b6b3-4f79-9273-fa724bb99cb8" />


### Infinity Norm of a Matrix
<img width="783" height="566" alt="Screenshot 2026-06-02 113923" src="https://github.com/user-attachments/assets/afcc2ba4-4dfa-4e72-a27e-1a8143c2782b" />
<img width="1234" height="313" alt="Screenshot 2026-06-02 113932" src="https://github.com/user-attachments/assets/681d601a-ca65-484a-8105-2d6eddb60474" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
