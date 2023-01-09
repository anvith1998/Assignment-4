# Assignment-4
#Write a Python program to create a lambda function that adds 25 to a given number passed in as an argument.

x=lambda x:x+25
print(x(25))

 ##write a Python program to triple all numbers of a given list of integers. Use Python map.
def fun(number):
    n = number*3
    return n
 
lists = [int(i) for i in input("enter the list of integers. Use Python map : ").split(",")]  
triple_no = list(map(fun, lists))           
print("sample : ", lists)               
print("Triple : ", triple_no)   
