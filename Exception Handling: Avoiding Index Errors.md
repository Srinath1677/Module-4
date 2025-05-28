# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```python
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
```
## Output
![447310569-d6475afe-a809-414a-9e06-98e2b81bb4ed](https://github.com/user-attachments/assets/6d61bff1-8aba-41ce-8aa1-ce2a0b39b44e)

## Result
Thus the program is executed successfully
