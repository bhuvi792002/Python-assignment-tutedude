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





    task 2


    # Task 2: Sum of Integers from 1 to 50 Using a Loop

# Initialize sum variable
total_sum = 0

# Loop through numbers from 1 to 50 and add them to total_sum
for num in range(1, 51):
    total_sum += num

# Display the final sum
print(f"The sum of integers from 1 to 50 is: {total_sum}")




task 3
# Task 1: Calculate Factorial Using a Function

# Define a function to calculate factorial
def factorial(n):
    if n < 0:
        return "Factorial is not defined for negative numbers."
    elif n == 0 or n == 1:
        return 1
    else:
        fact = 1
        for i in range(2, n + 1):
            fact *= i
        return fact

# Sample number
num = int(input("Enter a number: "))

# Call the function and print the result
print(f"Factorial of {num} is: {factorial(num)}")






    



