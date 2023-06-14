# Factorial_Number

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage
number = int(input("Enter a number: "))
result = factorial(number)
print(f"The factorial of {number} is: {result}")

def calculate_average(numbers):
    total = sum(numbers)
    average = total / len(numbers)
    return average

# Example usage
numbers = [5, 10, 15, 20, 25]
result = calculate_average(numbers)
print(f"The average is: {result}")
