# Average-Joe
# Practice with values and basic math
water_bottle = 1
case_of_water = water_bottle * 24
crate_of_water = case_of_water * 25
print(crate_of_water)
# This is to show that every 6th case of water is Cayla's water... modulo variable
cayla_water_1 = crate_of_water % 6
print(cayla_water_1)
# Practice multi line strings to print a long line of strings
thoughts = ''' Dear average joe,
I really enjoy writing code.
I hope that I can get get enough to create
even more complex stuff down the line.
This is exciting!'''
print(thoughts)
# practice more values to calculate half my age
my_age = 26
half_my_age = my_age / 2
print(half_my_age)
# practice with strings to print a greeting
greeting = "Hello world!"
name = "I am seth."
greeting_with_name = greeting + " " + name
print(greeting_with_name)
# notes for boolean expressions
1 == 1     # Evaluates to True as the operands are the same (equals to expression)

1 != 1     # Evaluates to False as the operands are the same (not equal expression)

2 != 4     # Evaluates to True as the operands are different 

3 == 5     # Evaluates to False as the operands are different
 
'7' == 7   # Evaluates to False as the operands are different types 
# first expression will store as true because the two values are equal. This uses the equal to operator
first_expression = 2 * 2 == 2 + 2
# seocond expression will store as true as well because the values are not equal. This uses the not equal operator
second_expression = 3 + 3 != 3 * 3 
# third expression will show as false because defining the value 9 makes the values not equal
third_expression = 3 * 3 == '9'
# printing the boolean expression answers
print(first_expression, second_expression, third_expression)
# extra practice with boolean expressions and conditional statements
# Entering a username for a coworker named dave. He is always on my computer and he uses someone else's username to throw me off his trail
user_name = "angela_catlady_87"
# if dave uses his name as the username then my program will tell dave to get off
if user_name == "Dave":
  print("Get off my computer Dave!")
 # dave is using someone elses username, so I set another conditional statement for if he uses her username
if user_name == "angela_catlady_87":
  print("I know it is you, Dave! Go away!")
# more practive with boolean and conditional statements
# setting variable values for x and y
x = 20
y = 20

# Write the first if statement here:
if x == y:
  print("These numbers are the same")

# scenario for college credits
credits = 120

# if the student has enough credits, then the system prints a message that tehy have enough
if credits >= 120:
  print("You have enough credits to graduate!")

# expanding on the graduation requirements with conditional statements
credits = 120
gpa = 3.4

if credits >= 120 and gpa >= 2.0:
  print("You meet the requirements to graduate")

# showing that they meet one of the graduation requirements
credits = 118
gpa = 2.0

if credits >= 120 or gpa >= 2.0:
  print("You have met at least one of the requirements.")

# expanding with "not"
credits = 120
gpa = 1.8

if not credits >= 120:
  print("You do not have enough credits to graduate.")
if not gpa >= 2.0 :
  print("Your GPA is not high enough to graduate.")
if not credits >= 120 and not gpa >= 2.0:
  print("You do not meet either requirement to graduate!")
# adding in "else"
credits = 120
gpa = 1.9

if (credits >= 120) and (gpa >= 2.0):
  print("You meet the requirements to graduate!")
else:
  print("You do not meet the requirements to graduate.")
 # practice with if, elif, else statements
 grade = 86
if grade >= 90:
  print("A")
elif grade >= 80:
  print("B")
elif grade >= 70:
  print("C")
elif grade>= 60:
  print("D")
else:
  print("F")



# practice with and
statement_one = (2 + 2 + 2 >= 6) and (-1 * -1 < 0)
# would express as false becuase of the second statement if false
statement_two = (4 * 2 <= 8) and (7 - 1 == 6)
# would express as true because both statements are true

# practice with "or"
True or (3 + 4 == 7)    # True
(1 - 1 == 0) or False   # True
(2 < 0) or True         # True
(3 == 8) or (3 > 4)     # False
# practice with not
statement_one = not (4 + 5 <= 9)  # false due to "not". not makes it opposite
statement_two = not (8 * 2) != 20 - 4  # true

