# Python-17
Write a Python program to search for an element in a given list of numbers.
L=[2,58,95,999,65,32,15,1,7,45]
n=int(input("enter the  number to be searched:"))
found=0
for x in L:
    if x==n:
        print("item found at position:",L.index(n)+1)
        found=1
    if found==0:
        print("Item not found")
Output
enter the  number to be searched:58
Item not found
item found at position: 2

=================== RESTART: C:/Python3.14/python programs.py =================
enter the  number to be searched:20
Item not found
Item not found
Item not found
Item not found
Item not found
Item not found
Item not found
Item not found
Item not found
Item not found
