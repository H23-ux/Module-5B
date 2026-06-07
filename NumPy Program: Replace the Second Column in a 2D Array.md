# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```Python
import numpy as np

original_array = np.array([[10, 20, 30], [40, 50, 60], [70, 80, 90]])

new_column = np.array([99, 88, 77])

modified_array = np.delete(original_array, 1, axis=1)

final_array = np.insert(modified_array, 1, new_column, axis=1)

print("Original Array:")
print(original_array)
print("\nNew Column to Insert:")
print(new_column)
print("\nFinal Array after replacing the second column:")
print(final_array)
```
## Output

<img width="482" height="476" alt="image" src="https://github.com/user-attachments/assets/f579e63e-144a-4441-80d1-0c79eef209f8" />

## Result
The **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position has been written and the output is verified.
