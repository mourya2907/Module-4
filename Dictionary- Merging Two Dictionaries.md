## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

~~~
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 99, 'd': 4}
def merge(d1, d2):
    return {**d1, **d2}
merged_dict = merge(dict1, dict2)
print(merged_dict)
~~~

## Output:
<img width="1437" height="211" alt="600728536-561e6dbb-138b-4ca3-b4f5-337d1b14c796" src="https://github.com/user-attachments/assets/9c422fac-efa9-4ca7-a1db-83794afd35f7" />


## Result:
Thus to write a Python program that merges two dictionaries and combines their key-value pairs is done successfully.
