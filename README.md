# Rent Calculator in Python

A simple Python program to calculate how much each person should pay for rent, food, and electricity.

## Features
- Takes **rent**, **food cost**, **electricity units used**, **charge per unit**, and **number of persons**
- Calculates the **total bill**
- Splits the total amount equally among all persons

## Input Values
- Total rent
- Total food ordered for snacking
- Electricity units spent
- Charge per unit
- Persons living in room/flat

## Output
- Total amount each person has to pay

## Python Code

```python
rent = int(input("Enter your hostel/flat rent = "))
food = int(input("Enter the amount of food ordered = "))
electricity_spend = int(input("Enter the total of electricity spend = "))
charge_per_unit = int(input("Enter the charge per unit = "))
persons = int(input("Enter the number of persons living in room/flat = "))

total_bill = electricity_spend * charge_per_unit

output = (food + rent + total_bill) // persons

print("Each person will pay = ", output)
