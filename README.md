# ass-1-17-02-22
#Write a program to print sum of even numbers and odd numbers
a= int(input("Enter the value : "))
even= 0
odd= 0
 
for a in range(1, a+ 1):
    if(a % 2 == 0):
        even=even+a
    else:
        odd=odd+a
 
print("sum of even number:",even)
print("sum of odd number:",odd)

output:
Enter the value:15
sum of even number:56
sum of odd number:64
