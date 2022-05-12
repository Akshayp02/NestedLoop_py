# NestedLoop_py
"""
Nested Loops = the "inner loop" will finish all of it's itration before
                finishing one itration of the "outer loop"

"""

rows = int(input(" how many row's ?"))
colum = int(input(" how many colom's ?"))
symbol = input("enter the symbol")

for i in range(rows):
    for j in range(colum):
        print(symbol , end="")
    print( )
