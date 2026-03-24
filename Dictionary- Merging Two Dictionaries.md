## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

# Define two dictionaries
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

# Function to merge dictionaries
def merge(d1, d2):
    return {**d1, **d2}

# Call function and print result
result = merge(dict1, dict2)
print("Merged Dictionary:", result)

## Output

<img width="631" height="213" alt="image" src="https://github.com/user-attachments/assets/86763cd6-4edc-4e88-94b7-12d8daafbfc2" />


## Result

Thus, the Python program successfully merges two dictionaries using the ** unpacking operator, where values from the second dictionary overwrite duplicate keys from the first.
