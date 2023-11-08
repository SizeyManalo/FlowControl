# FlowControl
Conditional Statements in Python This code provides examples of conditional statements in Python, including the if statement, if-else statement, and the use of if-elif-else. Conditional statements are used in Python to make decisions in your code based on specified conditions.

Conditional Statement
Conditional Statements:

If Statement
If else
Nested If
[ ]
# If Statement
# if condition:
  #block of code

emp = 101
if emp > 100:
  print("emp belongs to sales dept")
account_circle
emp belongs to sales dept
[ ]
employee =30000
if employee < 40000:
  print("employee belongs to grade B")
account_circle
employee belongs to grade B
[ ]
#Emp belongs to id 101 takes leave on Monday
Emp = 101
if Emp == 101:
  print("employee belongs to id 101 takes leave on Monday")
account_circle
employee belongs to id 101 takes leave on Monday
[ ]
Emp = 101
if Emp <101:
  print("employee belongs to id 101 takes leave on Monday")
[ ]
# if else statement
# if <expression>:
  #<condition>
#else:
  #<statement>

branch = "sales"
if branch == "HR":
  print("Employee is from different dept")
else:
  print("Employee belongs to same dept")
account_circle
Employee belongs to same dept
[ ]
# age = 30 then consider as senior or consider as a fresher
age = 30

if age == 30:
  print("Senior")
else:
  print("Fresher")
account_circle
Senior
[ ]
# if-elif
color = "White"
if color == "Red":
  print("color is Red")
elif color == "Blue":
  print("color is Blue")
elif color == "Black":
  print("color is Black")
else:
  print("color is not present")
account_circle
color is not present
[ ]
# for loop

names = ["John","Maria","Daniel"]
for name in names:
  print(name)
  if name == "Maria":
    break
account_circle
John
Maria
[ ]
names = ["John","Maria","Daniel"]
for name in names:
  if name == "Maria":
    continue
  print(names)
account_circle
['John', 'Maria', 'Daniel']
['John', 'Maria', 'Daniel']
[ ]
