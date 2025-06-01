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
      d3 = {4: 24, 2: 56, 1: 2, 3: 323, 5: 12, 6: 18}
      sorted_items = sorted(d3.items(), key=lambda item: item[1])
      print("Keys and Values sorted in alphabetical order by the value")
      print(sorted_items)  
## Sample Output
![image](https://github.com/user-attachments/assets/ef2a571d-e379-4f62-a530-b3a08d9fd746)

## Result
Thus, To write a Python program that sorts a dictionary's:- Keys in alphabetical order- Values in alphabetical order is verified and executed successfully.


