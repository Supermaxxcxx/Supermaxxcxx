- 👋 Hi, I’m @Supermaxxcxx
I've started 100 Days of Code: The Complete Python Pro Bootcamp training on 20-May-2024.
I've never been programming before.
I undertand that it will be challenging.
In this repository, I will show the different Python exercises I will be doing on the 100 Days of Code.
**Day number 1**
I have understand the only one function - and it is **PRINT**. :) 
**Day number 2**
i've modified a bit the execsise and insted of only weeks calculation the code now calculate the months as well
age = input()
years = 90 - int(age)
weeks = years * 52
month = years * 12
print(f"You have {weeks} weeks and {month} months left.")
_# TASK - If the bill was $150.00, split between 5 people, with 12% tip. _
#If the bill was $150.00, split between 5 people, with 12% tip. 
#Each person should pay (150.00 / 5) * 1.12 = 33.6
#Round the result to 2 decimal places.
print("Welcome to the tip calculator")
bill = float(input("What was the total bill? $"))
tip = int(input("How much tip would you like to give? 10, 12, or 15? "))
people = int(input("How many people to split the bill?"))
tip_as_percent = tip / 100
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = "{:.2f}".format(bill_per_person)
# FAQ: How to round to 2 decimal places?
# Find the answer in the Q&A here: https://www.udemy.com/course/100-days-of-code/learn/lecture/17965132#questions/13315048
print(f"Each person should pay: ${final_amount}")
