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
s = "google"
rev = s[::-1]

if s == rev:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
```

## Output

<img width="474" height="218" alt="image" src="https://github.com/user-attachments/assets/735c454b-80f0-4130-a5cc-82b7fc5b7ce3" />


## Result
The given program was executed successfully.
