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
```
# Define dictionary
dictionary = {'b': 30, 'a': 10, 'd': 40, 'c': 20}

sorted_by_keys = dict(sorted(dictionary.items()))

sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))


print("Original Dictionary:", dictionary)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="1393" height="221" alt="image" src="https://github.com/user-attachments/assets/e5d809f2-1a25-422e-adce-61e1b30ad764" />

## Result

