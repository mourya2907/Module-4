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
~~~
d={2: 56, 1: 2, 4: 24, 6: 18, 3: 323, 5: 12}
sorted_items=sorted(d.items(),key=lambda x:x[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
~~~

## Sample Output
<img width="1233" height="194" alt="600730379-f07244cc-6463-471e-80e7-136a794a05fc" src="https://github.com/user-attachments/assets/20eeb9d3-5ec0-4ff8-ad92-db10be0d88df" />

## Result:
Thus the Python program demonstrates how to sort a dictionary: Alphabetically by keys Alphabetically by values is done successfully.

