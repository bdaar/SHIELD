# Python Core
## >>> For better function, try the desired code in another Python file

# Variables
A = 1 and -3                                  # Integer ..........✔
B = 1.74                                      # Float ............✔
C = 7 + 5j                                    # Complex ..........✔
D = True or False                             # Boolean ..........✔
E = None                                      # None .............✔
F = "Hello World!"                            # String ...........✔
G = [1, 3 , "Hi"]                             # List .............✔
H = (1, 3 , "Hi")                             # Tuple ............✔
I = {"Name" : "Python" , "Type" : "Language"} # Dictionary .......✔
# Print and Type
# Show your data

print("-------( " + str(A) + " )-------( Type of variable: ", type(A), "\n")
print("-------( " + str(B) + " )-------( Type of variable: ", type(B), "\n")
print("-------( " + str(C) + " )-------( Type of variable: ", type(C), "\n")
print("-------( " + str(D) + " )-------( Type of variable: ", type(D), "\n")
print("-------( " + str(E) + " )-------( Type of variable: ", type(E), "\n")
print("-------( " + str(F) + " )-------( Type of variable: ", type(F), "\n")
print("-------( " + str(G[2]) + " )-------( Type of variable: ", type(G), "\n")
print("-------( " + str(H[0]) + " )-------( Type of variable: ", type(H), "\n")
print("-------( " + str(I["Name"]) + " )-------( Type of variable: ", type(I))

# Math
# Python has the capability of carrying out calculations.

print(10+2) #Plus
print(10-2) #Minus
print(10/2) #Division
print(10//2) #Floor Division: is used to determine the
# quotient of a division (the quantity produced by the
# division of two numbers).
print(10%2) # Modulo operator: is used to get the reminder of a division.
print(10*2) #Multiple
print(10**2) #Exponentiation

# Array or List
# Lists are used to store items. A list is created using square brackets
# with commas separating items.
Array1 = [0,1,2,3,"Hi",5.0,True]
Array2 = [0,1,2,3,["Hi",5.0],True]

# append a record
Array1.append(10)
print(Array1)

# Insert data on your destination 
MyArray = ["a","b","d","e"]
MyArray.insert(2, "c")
print(MyArray)

# Count the number of data: index
print(MyArray.index('a'))
print(MyArray.index('b'))
#print(MyArray.index('z')) # err: 'z' not in list ✔️

# Lenght records
Text = str("mhfjdkmmsklkakssakpolq") # 22 char
print(len(Text))

# If: if
# Else: else
# Esle if: elif
# Or: or
# And : and
# Equal: ==
# Not: !
# Not equal: !=
# Biger than: >
# Equal biger than: >=
# Smaller than: <
# Equal smaller than: <=

if 3 == 2:
    print("✔️")
elif 2+3 or 3+2 == 5 and 11-3 == 9 and 5>=3:
    print("✔️✔️")
else:
    print("❌")

# Loop: while & for

# while
# A while loop is used to repeat a block of code multiple times.

# sample 1
i = 1
while i <=5:
    print(i)
    i = i + 1
# sample 2
x = 1
while x < 10:
    if x%2 == 0:
        print(str(x) + " is Even")
    else:
        print(str(x) + " is Odd")





match a: // switch
case:
try:
except ValueError: // catch
a = "sTaRt"
print(a.split()) // Result: ["sTaRt"]

    x += 1 # or x = x + 1