# Assignment-4
#: Write a Python program to create a lambda function that adds 25 to a given number passed in as an argument.

x=lambda x:x+25
print(x(25))

 ##: write a Python program to triple all numbers of a given list of integers. Use Python map.
def fun(number):
    n = number*3
    return n
 
lists = [int(i) for i in input("enter the list of integers. Use Python map : ").split(",")]  
triple_no = list(map(fun, lists))           
print("sample : ", lists)               
print("Triple : ", triple_no)   


###: Write a Python program to square the elements of a list using map() function.

def square_num(n):
  return n * n
  
nums = [4, 5, 2, 9]

print("numbers: ",nums)
result = map(square_num, nums)
print("Square the elements():")
print(list(result))
