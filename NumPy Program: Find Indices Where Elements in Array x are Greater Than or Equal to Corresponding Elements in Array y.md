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

```python
import numpy as np

x = np.array([10, 20, 30, 40, 50])
y = np.array([15, 20, 25, 42, 48])

indices = np.where(x >= y)[0]

print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
```

## Output

<img width="354" height="311" alt="image" src="https://github.com/user-attachments/assets/dd4f4dbc-4e60-4b77-bc5e-6b56258e654b" />


## Result
The Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y` has been written and the output is verified.
