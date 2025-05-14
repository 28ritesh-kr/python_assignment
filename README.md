# python_assignment

# 1. Discount Calculator
bill = float(input())
if bill > 1000:
    discount = 0.20
elif bill > 500:
    discount = 0.10
else:
    discount = 0.0
final_amount = bill - (bill * discount)
print(final_amount)
python

# 2. Grade Categorizer
score = int(input())
if 90 <= score <= 100:
    print("Grade A")
elif 70 <= score <= 89:
    print("Grade B")
elif 50 <= score <= 69:
    print("Grade C")
elif 0 <= score < 50:
    print("Fail")
else:
    print("Invalid score")
python

# 3. Age Group Classifier
age = int(input())
if age < 13:
    print("Child")
elif age <= 19:
    print("Teen")
elif age <= 59:
    print("Adult")
else:
    print("Senior")
python

# 4. Even/Odd and Multiple of 5
num = int(input())
if num % 2 == 0:
    if num % 5 == 0:
        print("Even and divisible by 5")
    else:
        print("Even and not divisible by 5")
else:
    if num % 5 == 0:
        print("Odd and divisible by 5")
    else:
        print("Odd and not divisible by 5")
python

# 5. Login System (Membership Operator)
username = input()
if username in ['john', 'amy', 'sita']:
    print("Login successful")
else:
    print("Access denied")
python

# 6. Number Comparison Game
a = int(input())
b = int(input())
if a > b:
    print("First number is greater")
elif b > a:
    print("Second number is greater")
else:
    print("Both numbers are equal")
python

# 7. Eligibility for Voting and Driving
age = int(input())
if age >= 21:
    print("Eligible for voting and driving")
elif age >= 18:
    print("Eligible for voting")
else:
    print("Not eligible")
python

# 8. Leap Year Check
year = int(input())
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print("Leap year")
else:
    print("Not a leap year")
python

# 9. Login with Role
username = input()
role = input()
if username in ['john', 'amy', 'sita'] and role in ['admin', 'manager']:
    print("Login successful")
else:
    print("Login failed")
python

# 10. Arithmetic Operations
n1=int(input("enter the first number :"))
n2=int(input("enter the second number :"))
n3=input("enter the operation :")

match n3:
    case"+":
        print(f"the sum is : {n1+n2}")
    case "-":
        print(f"the difference is : {n1-n2}")
    case "*":
        print(f"the product is : {n1*n2}")
    case "/":
        print(f"the division is : {n1/n2}")
    case "_":
        print("invalid operation")    

# 11. Weather Alert System
temp = float(input())
if temp > 40:
    print("Heat Alert")
elif temp > 30:
    print("Warm")
else:
    print("Normal")
python

# 12. Password Strength Checker
password = input()
has_at = False
for ch in password:
    if ch == '@':
        has_at = True
        break
if len(password) >= 8 and has_at:
    print("Strong password")
else:
    print("Weak password")
python

# 13. ATM Withdrawal
balance = 10000
amount = int(input())
if amount <= balance and amount % 100 == 0:
    balance -= amount
    print("Withdrawal successful. Balance:", balance)
else:
    print("Withdrawal failed")
python

# 14. Divisibility Check
num = int(input())
if num % 3 == 0 and num % 5 == 0:
    print("Divisible by both 3 and 5")
elif num % 3 == 0:
    print("Divisible by 3")
elif num % 5 == 0:
    print("Divisible by 5")
else:
    print("Not divisible by 3 or 5")
python

# 15. Product Availability
product = input()
if product in ['pen', 'pencil', 'eraser']:
    print("Product available")
else:
    print("Product not available")
python

# 16. Triangle Validity
a = int(input())
b = int(input())
c = int(input())
if a + b > c and b + c > a and c + a > b:
    print("Valid triangle")
else:
    print("Invalid triangle")
python

# 17. Max of Three Numbers
a = int(input())
b = int(input())
c = int(input())
if a >= b and a >= c:
    print(a)
elif b >= a and b >= c:
    print(b)
else:
    print(c)
python

# 18. Marks Validity Check
marks = int(input())
if 0 <= marks <= 100:
    print("Valid marks")
else:
    print("Invalid marks")
python

# 19. Login Attempt System
username = input()
password = input()
if username == "admin" and password == "1234":
    print("Login successful")
else:
    print("Login failed")
python

# 20. Electricity Bill Slab
units = int(input())
if units <= 100:
    bill = units * 5
elif units <= 200:
    bill = units * 7
else:
    bill = units * 10
print("Total bill:", bill)
