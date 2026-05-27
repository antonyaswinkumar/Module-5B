# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program:

```
import numpy as np
l=eval(input("Enter the array: "))
a=np.array(l)
print("Given Array: ")
print(f"{a}")

print(f"Sorted array: \n{np.sort(a,axis=0)}")
```

## Output

<img width="671" height="386" alt="image" src="https://github.com/user-attachments/assets/e69bacf8-1177-48f7-9416-846938448b84" />


## Result:
Thus the **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
