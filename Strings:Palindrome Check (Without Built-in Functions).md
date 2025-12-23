# Strings-Palindrome Check in Python

## 🎯 Aim
To write a Python program to check whether the string entered is a **palindrome** or not.

## 🧠 Algorithm
1. Assign the string to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(s):
    a=s[::-1]
    if s==a:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
s=input()
palindrome(s)
```
## Output
<img width="1029" height="864" alt="image" src="https://github.com/user-attachments/assets/395eb4c6-b803-42b5-9e05-e70089a2cd3e" />

## Result
Thus,the given python program has been executed successfully.
