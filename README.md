# python-calculator
A simple Python calculator project created to practice programming fundamentals and Git/GitHub. It performs basic arithmetic operations including addition, subtraction, multiplication, and division. Built as part of my learning journey in software development and version control.
print("=== Simple Python Calculator ===")

num1 = float(input("Enter first number: "))
operator = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if operator == "+":
    print("Result:", num1 + num2)

elif operator == "-":
    print("Result:", num1 - num2)

elif operator == "*":
    print("Result:", num1 * num2)

elif operator == "/":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error: Division by zero is not allowed.")

else:
    print("Invalid operator!")
