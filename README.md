# calculator program 
# we will take the input 2 numbers 
# we need to save the operator also 

x= input("enter a number : ")
z= input("enter the operator: ")
y= input(" enter the second number: ")
x= int(x)
y= int(y)
if z=="+":
    print(f"the addition of {x} and {y} is {x+y}")
elif z=="-":
    print(f"the sub of {x} and {y} is {x-y}")
elif z=="*":
    print(f"the multiplaction of {x} and {y} is {x*y}")
elif z=="/":
    print(f"the division of {x} and {y} is {x/y}")
else:
    print(" the open which u have given is not there ")
