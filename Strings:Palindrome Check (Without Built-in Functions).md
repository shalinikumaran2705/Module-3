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
```python
s = "google"
rev = s[::-1]
if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```
## Output

<img width="462" height="165" alt="image" src="https://github.com/user-attachments/assets/d42f4187-0608-48e0-836f-f7f4dc953364" />

## Result
Thus, the Python program was successfully executed to check whether the given string is a palindrome.
