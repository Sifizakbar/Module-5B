# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

x = np.array([4, 7, 2, 9, 5])
y = np.array([3, 7, 5, 1, 5])

indices = np.where(x >= y)

print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
```
## Output
<img width="592" height="130" alt="image" src="https://github.com/user-attachments/assets/9adbb2a8-531e-44a1-80a7-978e0a63eab6" />

## Result
Thus, the NumPy program to find the indices where elements in array x are greater than or equal to the corresponding elements in array y was executed successfully and the output was verified.
