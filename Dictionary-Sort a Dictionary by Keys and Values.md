# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
dictionary = {'apple': 5, 'banana': 2, 'cherry': 8, 'date': 3}


print("Original dictionary:", dictionary)

sorted_by_keys = dict(sorted(dictionary.items()))
print("Dictionary sorted by keys:", sorted_by_keys)


sorted_by_values = dict(sorted(dictionary.items(), key=lambda item:item[1]))
print("Dictionary sorted by values:", sorted_by_values)


## Sample Output
<img width="826" height="270" alt="image" src="https://github.com/user-attachments/assets/9c91c5c1-b5fc-4936-90d6-e2518ea3f496" />

## Result
thus the code excuted sucessfully
