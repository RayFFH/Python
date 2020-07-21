def adder():
    x0 = float(input("Enter your 1st number : "))
    x1 = float(input("Enter your 2nd number : "))
    ans1 = x0 + x1
    print("The addition of {} and {} equals {}.".format(x0, x1, ans1))
    return


def subtractor():
    x0 = float(input("Enter your 1st number : "))
    x1 = float(input("Enter your 2nd number : "))
    ans1 = x0 - x1
    print("The subtraction of {} and {} equals {}.".format(x0, x1, ans1))
    return


def multiplier():
    x0 = float(input("Enter your 1st number : "))
    x1 = float(input("Enter your 2nd number : "))
    ans1 = x0 * x1
    print("The multiplication of {} and {} equals {}.".format(x0, x1, ans1))
    return


def divider():
    x0 = float(input("Enter your 1st number : "))
    x1 = float(input("Enter your 2nd number : "))
    ans1 = x0 / x1
    print("The division of {} and {} equals {}.".format(x0, x1, ans1))
    return


operator = input("Would you like to add,subtract,multiply or divide?").lower()
if operator == "add":
    adder()
elif operator == "subtract":
    subtractor()
elif operator == "multiply":
    multiplier()
elif operator == "divide":
    divider()
else:
    print("error")
