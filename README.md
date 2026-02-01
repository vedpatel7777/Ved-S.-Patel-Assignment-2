# Ved-S.-Patel-Assignment-2
Control Structures in Python
# Task 1
number = int(input("Enter an integer: "))

# Check if the number is even or odd
if number % 2 == 0:
    print(f"{number} is even.")
else:
    print(f"{number} is odd.")

# Task 2
total = 0
for i in range(1, 51):
    total += i
print(f"The sum of integers from 1 to 50 is: {total}")
