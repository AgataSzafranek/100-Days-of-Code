# 100-Days-of-Code

Day 1 

print("Welcome to the Band Name Generator!")
city = input("Which city did you grew up in?\n")
pet = input("What is the name of your pet?\n")
print("Your band name could be: " + city + " " + pet)

Day 2 

print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("What percentage tip would you like to give? 10 12 15 "))
people = int(input("How many people to split the bill? "))
tip_as_percent = tip / 100
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = round(bill_per_person, 2)
print(f"Each person should pay: ${final_amount}")

Day 3
