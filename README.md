# Let's Stay Healthy Project 

# 1. BMI calculation

# User's input : weight and height
weight = int(input("Please enter your weight in pounds: "))
height = int(input("Please enter your height in inches: "))

# BMI formula
BMI =  weight * 703 / height ** 2

# Let User Know of their BMI number
print("Your BMI is: ", f"{BMI: .2f}")

# Let User Know What the BMI number means
if BMI < 18.5 :
    print("You are underweight.")
elif BMI >= 18.5 and BMI <= 24.9:
    print("You are normal.") 
elif BMI >= 25.0 and BMI <= 29.9:
    print("You are overweight.")   
else : 
    print("You are Obsese. See a doctor.")
