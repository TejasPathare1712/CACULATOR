print("^^^^^^^^^^^MINI CALCULATOR^^^^^^^^^^^")

num1 = float(input("ENTER FIRST NUMBER HERE"))
num2 = float(input("ENTER SECOND NUMBER HERE"))

print("PRESS 1 FOR ADDITION\n PRESS 2 FOR SUBTRACTION\nPRESS 3 FOR MULTIPLICATION\nPRESS 4 FOR DIVISION")

choice = int(input("Enter Your Choice from 1-4:-"))

if choice == 1:
   print(num1+num2)
elif choice == 2:
    print(num1-num2)
elif choice == 3:
    print(num1*num2)
elif choice == 4:
    print(num1/num2)
else:
    print("INVALID OPERATION")
             
