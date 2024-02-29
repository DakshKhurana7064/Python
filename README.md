# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
b) Print your name by using for loop

c) check the user name is palindrome or not

name = "Daksh"
for i in range(7):
    if i in [0, 6]:
        print("* " * 3 + " ")
    elif i in [1, 2, 3, 4, 5]:
        print("*" + " " * 6 + "*")
    else:
        print("* " * 3)


for letter in name:
    print(letter)


if name.lower() == name[::-1].lower():
    print("The name is a palindrome")
else:
    print("The name is not a palindrome")
