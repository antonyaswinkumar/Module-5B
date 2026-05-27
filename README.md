## Python Programming Module 5
## Name: Antony Aswin Kumar L
## Register Number: 212225040024

## Ex:1  NumPy Program: Column-wise Sorting of a 2D Array

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




## Ex:2  NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

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

## 🧾 Program:

```
import numpy as np  
x=eval(input("Enter the First array: ")) 
y=eval(input("Enter the Second array: ")) 
l1=np.array(x) 
l2=np.array(y) 
print()
print(np.where(l1>l2)) 
print(np.where(l1==l2))
```


## Output:

<img width="631" height="309" alt="image" src="https://github.com/user-attachments/assets/f04a6df4-103e-4c82-a2e4-be68952b916e" />


## Result
Thus the Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array y.





## Ex:3  NumPy Program: Replace the Second Column in a 2D Array

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
