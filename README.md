# 🧑‍🏫 Teaching Assistantship (TA) – Python Programs

This repository contains simple Python programs useful for **Teaching Assistantship (TA)** demonstrations.
The programs cover topics like **string formatting**, **table alignment**, and **number formatting**.

---

## 📌 Program 1: Display Table of Students with Proper Alignment

### **Output**

```
Sr No  Name            Subject    Grade   Percentage
-------------------------------------------------------
1      Nisha Patel     Math       A       92
2      Aarav Modi      Science    B+      85
3      Jiya Shah       English    A+      96
```

### **Python Code**

```python
# Program to display table of items with proper alignment

print(f"{'Sr No':<6} {'Name':<15} {'Subject':<10} {'Grade':<7} {'Percentage':<10}")
print("-" * 55)

print(f"{1:<6} {'Nisha Patel':<15} {'Math':<10} {'A':<7} {92:<10}")
print(f"{2:<6} {'Aarav Modi':<15} {'Science':<10} {'B+':<7} {85:<10}")
print(f"{3:<6} {'Jiya Shah':<15} {'English':<10} {'A+':<7} {96:<10}")
```

---

## 📌 Program 2: Format Float Number to 2 Decimals, 3 Decimals, and Width 10

### **Sample Output**

```
2 decimals: 37.26
3 decimals: 37.257
Width 10:      37.26
```

### **Python Code**

```python
# Program to format a float number

num = float(input("Enter a float number: "))

print("2 decimals:", format(num, ".2f"))
print("3 decimals:", format(num, ".3f"))
print("Width 10:", format(num, "10.2f"))
```

---

## ✔️ Topics Demonstrated

* String alignment (`<`, `>`, fixed width)
* f-strings in Python
* Using `format()` for number formatting
* Table-style output formatting
