# CSA1784-Artificial-intelligence
def add(a,b):
    return a+b
def sub(a,b):
    return a-b
def mul(a,b):
    return a*b
def div(a,b):
    return a/b

print("Please select an operation: /n")
print("1.addition")
print("2.subtraction")
print("3.multiplication")
print("4.division")

choice = int(input("please enter a choice 1/2/3/4: "))
num_1 = int(input("please enter the first number: "))
num_2 = int(input("please enter the second number: "))

if choice == 1:
            print(num_1,"+",num_2,'=',add(num_1,num_2))
elif choice == 2:
            print(num_1,"-",num_2,'=',sub(num_1,num_2))
elif choice == 3:
            print(num_1,"*",num_2,'=',mul(num_1,num_2))
elif choice == 4:
            print(num_1,"/",num_2,'=',div(num_1,num_2))
else:
    print("This is an invalid input")
