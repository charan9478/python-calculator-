# python-calculator-
I created my first python calculator.
#python calculator

operator = input("enter the operator(+ * %  / - **):")
num1 = float(input("enter a number:"))
num2 = float(input("enter a number:"))

if operator== "+":
    print(num1+num2)
elif operator=="*":
    print(num1*num2)
elif operator=="%":
    print(num1 % num2)
elif operator == "**":
    print(num1**num2)
elif operator =="-":
    print(num1-num2)
elif operator == "/":
    print(num1 / num2) 
else:
    print("enter the operator please:")
    
