# Assignment 3: Python Operators (`is` vs `in`)

## Introduction
Python has different types of **operators** that perform various tasks. Today, we will understand the difference between `is` and `in` in the simplest way possible so that anyone can learn how to use them correctly.

---

## `is` Operator (Same Object?)
The `is` operator is an **identity operator** that checks **whether two variables refer to the same object in memory**. This means that even if two variables have the same values, they must also share the same memory location to return `True`.

### Simple Example:
Imagine you have two friends, Alex and John. They may look similar, but they are two different people. Similarly, if two lists have the same data, they can still be stored separately in memory.

```python
x = [1, 2, 3]
y = [1, 2, 3]
z = x

print(x is y)  # False (because they are stored separately in memory)
print(x is z)  # True (because z and x point to the same object)
```

### In Simple Words:
- `x is y` ❌ (because `x` and `y` are different objects)
- `x is z` ✅ (because `x` and `z` point to the same object)

---

## `in` Operator (Exists Inside?)
The `in` operator is a **membership operator** that checks **whether a value exists inside a list, tuple, string, or other collections**.

### Simple Example:
Imagine you have a bag with an apple, a banana, and a mango. If you ask, "Is there a banana in the bag?" the answer will be "Yes." But if you ask, "Is there a grape?" the answer will be "No."

```python
fruits = ["apple", "banana", "mango"]
print("banana" in fruits)  # True (because banana is in the list)
print("grape" in fruits)    # False (because grape is not in the list)
```

### In Simple Words:
- `"banana" in fruits` ✅ (because `banana` is in the list)
- `"grape" in fruits` ❌ (because `grape` is not in the list)

---

## Difference Between `is` and `in`
| Feature  | `is` (Same Object?) | `in` (Exists Inside?) |
|----------|------------------|------------------|
| Purpose  | Checks if two objects share the same memory location | Checks if a value exists in a collection |
| Returns  | `True` or `False` | `True` or `False` |
| Example  | `a is b` | `"apple" in fruits` |

---

## Venn Diagram Representation
Below is a simple **Venn Diagram** to visually represent the difference between `is` and `in`:

```
          +------------------+------------------+
          |                  |                  |
   `is`  |  Same memory     |   No relation    |
          |  location check  |                  |
          |                  |                  |
          +------------------+------------------+
          |                  |                  |
   `in`  |  Checks if       |   No memory      |
          |  element exists  |   comparison     |
          |  in collection   |                  |
          |                  |                  |
          +------------------+------------------+
```

For a colorful Venn diagram, you can create one using online tools or Python’s `matplotlib` library.

---

## Conclusion
✅ Use `is` when you want to check if **two variables refer to the same object in memory**.
✅ Use `in` when you want to check if **a value exists inside a collection like a list or string**.

---

### 🎯 Learned it? Now try it yourself! 🚀

