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

