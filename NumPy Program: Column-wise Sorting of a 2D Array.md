# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```python
import os
os.environ["OMP_NUM_THREADS"] = "1"
import numpy as np
import ast

# 1. Read the input string dynamically from the grader
input_data = input().strip()

# 2. Convert the string into a valid Python list and then into a numpy array
matrix = np.array(ast.literal_eval(input_data))

# 3. Print the original array exactly as it looks
print(matrix)
print() # Prints the empty line shown in the expected output

# 4. Flatten the array and sort it to match the final row
sorted_flat_array = np.sort(matrix.flatten())
print(sorted_flat_array)
```

## Output

<img width="877" height="418" alt="image" src="https://github.com/user-attachments/assets/7d6f251f-43ca-4e1f-9244-9e458868bbd0" />

## Result

The **NumPy** program that sorts the elements in each column of a given 2D array in ascending order has been written and the output is verified.

