# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re

# Step 1: Original list of words
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []

# Step 2: Filter words that do NOT contain the letter 'e'
for i in items:
    if not re.search(r"e", i):
        l1.append(i)

# Step 3: Print the filtered list
print("Words without the letter 'e':", l1)
```
## Output
```
Words without the letter 'e': ['goal', 'sit']
```
## Result
The program successfully filtered out words containing the letter 'e' using regular expressions.

