# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equation and assign in np.array
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
end the program
## Program:
```
import numpy as np
def find_matrix_rank(matrix):
    """
    Calculates the rank of a matrix using NumPy.
    try:
        np_matrix = np.array(matrix)
        rank = np.linalg.matrix_rank(np_matrix)
        return rank
    except Exception as e:
        print(f"An error occurred: {e}")
        return None

# Given matrix
matrix = [[5, -3, -10],
          [2, 2, -3],
          [-3, -1, 5]]

# Calculate the rank
rank = find_matrix_rank(matrix)

# Print the rank
if rank is not None:
    print(f"The rank of the matrix is: {rank}")
```
    
## Output:![Screenshot 2025-03-27 194647](https://github.com/user-attachments/assets/0d05bcc0-eb79-40ca-b706-02630b8f9aa8)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

