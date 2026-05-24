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
```
import pandas as pd

student_data1 = {
    'Name': ['Arun', 'Bala'],
    'Marks': [85, 90]
}

student_data2 = {
    'Name': ['Cathy', 'David'],
    'Marks': [78, 88]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

new_df = pd.concat([df1, df2], axis=0)

print(new_df)
```
## Output
<img width="532" height="226" alt="image" src="https://github.com/user-attachments/assets/7363b612-1cd0-466f-b857-3de56c9910a7" />

## Result
Thus, the Python program using Pandas to join two DataFrames row-wise using pd.concat() was executed successfully and the output was verified.
