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
def palindrome(a):
    d=a[::-1]
    if a==d:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
a=input()
palindrome(a)
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-21 121406" src="https://github.com/user-attachments/assets/4ba4b97c-1e4e-499b-9474-172602e64661" />

## Result
successfully created  a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.
