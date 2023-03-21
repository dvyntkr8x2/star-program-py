# star-program-py
credits to the respective youtuber
This is a python program to print star pattern program
example: 

*
**
***
****
----------------------------------------------------------------------

num= int(input("enter no. of rows"))
for i in range(1,num+1):
    for j in range(1,i+1):
        print("*", end= " ")
    print()
