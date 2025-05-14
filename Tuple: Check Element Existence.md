# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
# Step 1: Define the tuple
x = ('a', 'b', 'n', 1, 3, 8, 5)

# Step 2 & 3: Check for element existence
check_n = 'n' in x
check_8 = 8 in x

# Step 4: Print the results
print("'n' exists in tuple:", check_n)
print("8 exists in tuple:", check_8)
```
## Output
```
'n' exists in tuple: True
8 exists in tuple: True
```
## Result
The program successfully checks and confirms the existence of both 'n' and 8 in the tuple.

