## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4, 'e': 5}


def merge(d1, d2):
    merged_dict = {**d1, **d2}  
    return merged_dict


result = merge(dict1, dict2)
print("Merged dictionary:", result)


## Output
<img width="693" height="192" alt="image" src="https://github.com/user-attachments/assets/e4a6dd9a-f9de-494e-8e29-1f7c296a886b" />

## Result
thus the code excuted sucessfully
