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
~~~
try:
    n=int(input())
    a=[]
    for i in range(n):
        num=int(input())
        a.append(num)
    index=int(input())    
    print(a)
    print(a[index])
except IndexError:
    print(f"{index} is not accepted")
~~~

## Output
<img width="712" height="377" alt="600731448-d96e6192-b83f-4ee9-a5a3-9a9e4521401b" src="https://github.com/user-attachments/assets/5800b2a1-2a5f-4578-b933-c3d7e5cf0eef" />


## Result:
Thus to write a Python program that handles an IndexError when trying to access an element beyond the available range of a list is done successfully.
