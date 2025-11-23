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

x=np.array(eval(input()))
y=np.array(eval(input()))
gt=np.where(x>y)
eq=np.where(x==y)
print(gt)
print(eq)
```

## Output

<img width="1132" height="257" alt="image" src="https://github.com/user-attachments/assets/a39f8471-954f-49ce-9a32-1fce75bbd3cc" />

## Result
Thus, the program that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y was executed successfully.

