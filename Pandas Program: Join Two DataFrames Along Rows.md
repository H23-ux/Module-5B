# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```R
import pandas as pd

student_data1 = pd.DataFrame(
    {
        "student_id": ["S1", "S2", "S3", "S4", "S5"],
        "name": ["Danniella Fenton", "Ryder Foley", "Zayn Ahmed", "Demarco Allen", "Magnus Harvey"],
        "marks": [200, 210, 190, 222, 199],
    }
)

student_data2 = pd.DataFrame(
    {
        "student_id": ["S4", "S5", "S6", "S7", "S8"],
        "name": ["Scarlett Wright", "Alexie Khan", "Osian Barker", "Reema Colley", "Geraint Davies"],
        "marks": [201, 200, 198, 219, 201],
    }
)

result_data = pd.concat([student_data1, student_data2], axis=0)

print(result_data)
```

## Output

<img width="409" height="406" alt="image" src="https://github.com/user-attachments/assets/12e5fbd0-3cc8-48ae-9483-5d4f62cc1a1a" />

## Result

The Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame has been written and hence the output is verified.
