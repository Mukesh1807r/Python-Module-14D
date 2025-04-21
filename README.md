# Inserting Elements at Front End of Deque using Built-in Function

## 📌 Aim
To write a Python program that inserts the characters `'h'`, `'o'`, and `'n'` at the **front** of a **deque** using the `appendleft()` function from the `collections` module.

---

## 🛠 Procedure
1. Initialize an empty deque using `deque()`.
2. Insert characters into the deque using `append()` function to add them at the rear of the deque.
3. Use the `appendleft()` function to insert `'h'`, `'o'`, and `'n'` at the **front** of the deque.
4. Print the updated deque after all the insertions.

---

## 💻 Program

```python
from collections import deque

# Initialize an empty deque
dq = deque()

# Insert elements at the rear end of the deque
for i in range(3):
    a = input()
    dq.append(a)

# Insert 'h', 'o', 'n' at the front end of the deque
dq.appendleft('h')
dq.appendleft('o')
dq.appendleft('n')

# Print the updated deque
print("The deque after appending at right is :")
print(dq)
```
---
## Output 

![image](https://github.com/user-attachments/assets/288c930d-c939-4fe1-91db-f75ea3cb25e4)

---

## Result 

Thus, the program was successfully created and executed to insert elements at the front end of the deque.




