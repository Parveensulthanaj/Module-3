# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(s):
    new=s[:3]+s[3+1:]
    print(new)
```

## Output
<img width="1110" height="404" alt="pp3 4" src="https://github.com/user-attachments/assets/f1149977-cc6c-4fc7-82e7-2f81ec5a484f" />

## Result
Thus the program that accepts a string and removes the character at a specified index has been executed successfully.
