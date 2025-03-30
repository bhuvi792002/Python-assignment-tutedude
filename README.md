# Task 1: Check if a Number is Even or Odd

# Taking input from the user
try:
    num = int(input("Enter an integer: "))

    # Check if the number is even or odd
    if num % 2 == 0:
        print(f"{num} is an Even number.")
    else:
        print(f"{num} is an Odd number.")

except ValueError:
    print("Invalid input! Please enter an integer.")

