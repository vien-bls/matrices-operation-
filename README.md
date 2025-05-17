import numpy as np

# 1. Creating Matrices
# 1st Matrix using initials (B, L, S) and 2nd letters (e, o, i)
A = np.array([[2, 12, 19], 
              [5, 15, 9]])

# 2nd Matrix using student number 2023-40620
B = np.array([[2, 0, 2], 
              [6, 2, 0]])

# 1.b Print both matrices
print("Matrix A (1st Matrix):\n", A)
print("Matrix B (2nd Matrix):\n", B)

# 2. Matrix Addition
C = A + B
print("Matrix C (A + B):\n", C)

# 3. Scalar Multiplication
D = A * 2
print("Matrix D (A * 2):\n", D)

# 4. Matrix Transpose
E = B.T
print("Matrix E (Transpose of B):\n", E)

# 5. Matrix Multiplication (C x E)
F = np.matmul(C, E)
print("Matrix F (C x E):\n", F)

# 6. Sum of All Elements in Matrix C
sum_C = np.sum(C)
print("Sum of all elements in Matrix C:", sum_C)
