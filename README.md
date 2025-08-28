# 📘 Week Two Python Assignment

## 📚 Description

This repository contains my solution for **Week Two Assignment** in Python programming.  
The task focuses on practicing list operations such as appending, inserting, extending, removing, sorting, and finding element indices.

---

## 📝 Assignment Instructions

1. Create an empty list called `my_list`.
2. Append the following elements to `my_list`: `10, 20, 30, 40`.
3. Insert the value `15` at the **second position** in the list.
4. Extend `my_list` with another list: `[50, 60, 70]`.
5. Remove the **last element** from `my_list`.
6. Sort `my_list` in **ascending order**.
7. Find and print the **index of the value 30** in `my_list`.

---

## 💻 Solution

The full solution is implemented in **[assignment.py](assignment.py)**.  
Below is a quick snippet:

```python
my_list = []

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()
my_list.sort()

index_of_30 = my_list.index(30)

print("Final List:", my_list)
print("Index of 30:", index_of_30)

```
