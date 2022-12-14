# To-find-HCF-and-LCMof-any-two-numbers
It is a python program to find HCF and LCM of two numbers by user
 code starts from here:
 a=int(input('enter the first number='))
b=int(input('enter the second number'))
x=a
y=b
while a!=b:
    if a>b:
        a=a-b
    else:
        b=b-a
print("HCF=",a)
LCM=(x*y)//a
print('LCM=',LCM)
