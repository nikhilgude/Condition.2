# Condition.2
nested if for checking the number is both pos and even
num = int(input("enter the number"))
if num>0:
    print("positive number")
    if num%2==0:
        print("even")
    else:
        print("odd")
else:
    print("number is non positive")
