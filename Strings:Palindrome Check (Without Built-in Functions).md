# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
# Step 1: Assign the string
s = "google"

# Step 2: Reverse the string manually
rev = ""
for i in range(len(s)-1, -1, -1):
    rev += s[i]

# Step 3: Compare original and reversed strings
if s == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
```
The string is not a palindrome.
```
## Result
The program correctly identifies that "google" is not a palindrome.
