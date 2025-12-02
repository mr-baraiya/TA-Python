# TA
This is for Teching Assitantship.

Sr No  Name            Subject    Grade   Percentage
-------------------------------------------------------
1      Nisha Patel     Math       A       92
2      Aarav Modi      Science    B+      85
3      Jiya Shah       English    A+      96


# Program to display table of items with proper alignment

print(f"{'Sr No':<6} {'Name':<15} {'Subject':<10} {'Grade':<7} {'Percentage':<10}")
print("-" * 55)

print(f"{1:<6} {'Nisha Patel':<15} {'Math':<10} {'A':<7} {92:<10}")
print(f"{2:<6} {'Aarav Modi':<15} {'Science':<10} {'B+':<7} {85:<10}")
print(f"{3:<6} {'Jiya Shah':<15} {'English':<10} {'A+':<7} {96:<10}")


# Program to format a float number
2 decimals: 37.26
3 decimals: 37.257
Width 10:      37.26

num = float(input("Enter a float number: "))

print("2 decimals:", format(num, ".2f"))
print("3 decimals:", format(num, ".3f"))
print("Width 10:", format(num, "10.2f"))
