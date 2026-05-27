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

```
import numpy as np
orig=np.array(eval(input("Enter the Original array: ")))
new=np.array(eval(input("Enter the new column: ")))
print("Printing Original array")
print(orig)
modif=np.delete(orig,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(modif)
result=np.insert(modif,1,new,axis=1)
print("Array after inserting column 2 on axis 1")
print(result)
```

## Output:

<img width="744" height="584" alt="image" src="https://github.com/user-attachments/assets/959f0858-a71b-48b6-b18b-c4f521fd2062" />


## Result:
Thus the **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is executed successfully.
