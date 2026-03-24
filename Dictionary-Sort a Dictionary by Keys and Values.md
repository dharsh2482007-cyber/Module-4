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

# Define a dictionary
d = {'banana': 'yellow', 'apple': 'red', 'grape': 'purple', 'orange': 'orange'}

# Sort dictionary by keys
sorted_by_keys = dict(sorted(d.items()))

# Sort dictionary by values
sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))

# Display results
print("Original Dictionary:", d)
print("Dictionary sorted by keys:", sorted_by_keys)
print("Dictionary sorted by values:", sorted_by_values)

## Sample Output

<img width="832" height="322" alt="image" src="https://github.com/user-attachments/assets/308db917-bb43-4b01-9d69-129520a4e806" />


## Result


Thus, the Python program successfully sorts the dictionary both by keys and by values using the sorted() function.
