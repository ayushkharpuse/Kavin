# calculate two numbers
operator = (input("Choose any operator: +,-,*,/, "))
a = (int(input("\n enter first number : ")))
b = (int(input("\n Enter second number : ")))

while True:
    if operator == "+":
        print("sum of ",a," and",b," is", a+b)
        break

    elif operator == "-":
        print("div of ",a," and",b," is", a-b)
        break

    elif operator == "*":
        print("mul of ",a," and",b," is", a*b)
        break

    elif operator == "/":
        print("sub of ",a," and",b," is", a/b)
        break

    else:
        print("you are choose Wrong operator,\n plese Try again!")
        break
