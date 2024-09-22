# Python1
# USING WHILE LOOP
# To print the numbers from 1 to 100
# i = 1
# while i <= 100:
#     print (i)
#     i += 1

# To print the numbers from 20 to 1
# i = 20
# while i >=1:
#     print(i)
#     i -= 1

# To print the multiplication of number n
# n= int(input("Enter the number:"))
# i=1
# while i<=10:
#     print(n,"*",i,"=",n*i)
#     i += 1

# To print numbers in the list
# a= [1,23,34,56,67,89]
# i= 0
# while i<len(a):
#     print(a[i])
#     i+=1

# To print x in list
# b= [1,23,34,56,67,89]
# x = 67
# i = 0
# while i<len(b):
#     if(b[i] == x):
#         print("found at idx", i)
#     i += 1

# USING FOR LOOP
# Printing the elements in the list
# list = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

# for i in list:
#     print(i)

# Finding x in the list
# list = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

# x = 4
# for i in list:
#     if (i == x):
#         print("num found")
#         break
#     else:
#         print("num not found")

# Using range
# n = int(input("Enter the Number:"))
# i = 0
# for i in range(1, 11):
#     print(n*i)
#     i += 1

# Finding sum of first N natural numbers
# N= int(input())
# i = 0
# sum = 0
# while(i<=N):
#     sum += i
#     i+=1
# print(sum)

# Printing even numbers from 1 to 100 using for loop
# for i in range(0,101,2):
#     print(i)

# rows = 5
# for i in range(1, rows+1):
#     for j in range(i):
#         print('*', end='')
#     print()

# for i in range(10, 0, -1):
#     print(i)
# Initialize the sum to 0
# i = 0
# n = 1
# while (i<= 5):
#     print(n+i)
#     i += 1
# Printing pattern using nested for loop
# for i in range(4):
#     for j in range(1,5):
#         print(j, end=' ')
#     print()
# def avg(a, b, c):
#     sum = a+b+c
#     avg = sum/3
#     print(avg)
#     return avg
# avg(1,2,3)

# To find max of 2 numbers using functions 
# def find_max(a, b):
#     if(a>b):
#         print("a is GREATER")
#     else:
#         print("b is GREATER")
# find_max(5, 1)
# find_max(12, 20)

# To print patterns
# right angle triangle with *'s

# n = 5 #number of rows
# for i in range(n):  #Outer loop for rows
#     for j in range(i+1):  #Inner loop for colomns
#         print("*", end ='')
#     print() # To print on next line

# #left angle triangle with *'s

# n = 5
# for i in range(n):
#     for j in range(i,n):
#         print(' ',end='')
#     for j in range(i+1):
#         print("*", end='')
#     print()

# #To print pyramid

# n = 5
# for i in range(n):
#     for j in range(i, n):
#         print(' ', end= '')
#     for j in range(i):
#         print("*", end='')
#     for j in range(i+1):
#         print("*", end='')
#     print()

# To print reverse pyramid
# n = 5
# for i in range(n):
#     for j in range(i+1):
#         print(' ',end= '')
#     for j in range(i,n-1):
#         print("*",end='')
#     for j in range(i,n):
#         print("*",end= '')
#     print()

# To print diamond

# n = 5
# # for i in range(n-1):
#     for j in range(i, n):
#         print(' ', end= '')
#     for j in range(i):
#         print("*", end='')
#     for j in range(i+1):
#         print("*", end='')
#     print()
# for i in range(n):
#     for j in range(i+1):
#         print(' ',end= '')
#     for j in range(i,n-1):
#         print("*",end='')
#     for j in range(i,n):
#         print("*",end= '')
#     print()

# #File I/O

# #Creating a new file containing data:
# with open("test.txt","w") as f:
#     data = f.write("I am hemanth\nStudying Tenth Class.")
# print(data)

# #Editing a file with new data:
# with open("test.txt","r") as f:
#     data_one = f.read()
# new_data = data_one.replace("hemanth","Shiva Prasad")
# print(new_data)

# #Updating the data:
# with open("test.txt","w") as f:
#     f.write(new_data)


# with open("test.txt","r") as f:
#     data_one = f.read()
# new_data_o = data_one.replace("Studying Tenth Class","Learning to code")
# print(new_data_o)

# #Updating the data:
# with open("test.txt","w") as f:
#     f.write(new_data_o)

# #Finding the word in the file
# word = "I am"
# with open("test.txt","r") as f:
#     data = f.read()
#     if(data.find(word) != -1):
#         print("FOUND")
#     else:
#         print("NOT FOUND")

# To print factorial of n

# n = int(input())
# result = 1
# for i in range(1, n+1):
#     result *= i

# print("The factorial of n is:", result)
