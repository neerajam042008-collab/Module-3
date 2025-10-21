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
i = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
a=r"^[^e]*$"
d=(n for n in i if re.match(a,n))
print(list(d))
```
## Output
<img width="523" height="185" alt="Screenshot 2025-10-21 120705" src="https://github.com/user-attachments/assets/d0ea3cba-3753-4609-96f7-fc860e00c235" />

## Result
successfully created a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (re
