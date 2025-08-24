# Assigment2.py
num = int(input("Enter a number: "))
if (num % 2) == 0:
    print(f"{num} is an Even. ")
else:
    print(f"{num} iS an odd. ")
total_sum = 0   # to store the sum

for num in range(1, 51):   # loop from 1 to 50
    total_sum = total_sum + num   # add each number

print("The sum of numbers from 1 to 50 is:", total_sum)
