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
items=['goal','new','user','sit','eat','dinner']
filtered_items=[item for item in items if 'e' not in item]
print(filtered_items)
```
## Output
<img width="1109" height="335" alt="pp3 2" src="https://github.com/user-attachments/assets/d9ebd00a-ec44-4a19-aeeb-242d85825f0b" />


## Result
Thus program that filters out and returns all elements from a list has been excuted successfully.
