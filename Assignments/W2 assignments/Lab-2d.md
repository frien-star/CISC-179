### 1. User Input
#### a. 
```python 
weight = float(input("What is your weight in kilograms? \n"))
Pounds = weight * 2.2
print("You weigh", Pounds, "pounds")
```
#### 1b.
``` python
# 1b.
netBalance = float(input("What is your total balance? \n"))
# Total balance
payment = float(input("How much are you paying for? \n"))
# Payment made
d1 = int(input("How many days is the billing period? \n"))
# Days in the billing cycle
d2 = int(input("How many days did it take to pay before the billing cycle ended? \n"))
# Days payment was made before billing cycle
averageDailyBalance = (netBalance * d1 - payment * d2)/d1
interest = float(averageDailyBalance * 0.0152)
print("Your accrued interest is $", interest)
```
#### 1c,
``` python
# 1c.
Car_A_speed = float(input("How fast was car A in miles per hour? "))
Car_B_speed = float(input("How fast was car B in miles per hour? "))
Elapsed_time = float(input("How hours has passed since then? Enter minutes as a decimal:  "))
Distance_Between_cars = int(((Car_A_speed * Elapsed_time)**2 + (Car_B_speed * Elapsed_time)**2)**0.5)
print("They are about", Distance_Between_cars, "miles apart.")
```
### 2. Troubleshooting
a. True,  variable is stored as a string   
b. True, Underscores are an exception to variable names   
c. False, Exclamation marks are not an exception when naming variables- causes error   
d. False, Cannot use commands or keywords when naming variables   
e. False, False alone is keyword/command
