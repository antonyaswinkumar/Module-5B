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
a=eval(input("Enter the dataset1 :"))
b=eval(input("Enter the dataset2 :"))
df1=pd.DataFrame(a)
df2=pd.DataFrame(b)
print("\n")
print("Original DataFrames:")
print(df1)
print("-"*20)
print(df2)
print()
mer=pd.concat([df1,df2])
print("Join the said two dataframes along rows:")
print(mer)
```

## Output

<img width="767" height="735" alt="image" src="https://github.com/user-attachments/assets/5c73b075-4fa7-45ed-8cd5-5ba1c2966d57" />


## Result:
Thus the Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is executed successfully.
