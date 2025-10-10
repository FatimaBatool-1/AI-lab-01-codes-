# AI-lab-01-codes-
# Task :01
num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
# Task: 02
num = int(input("Enter a number: "))

if num > 1:
    for i in range(2, num):
        if num % i == 0:
            print(num, "is not a prime number.")
            break
    else:
        print(num, "is a prime number.")
else:
    print(num, "is not a prime number.")
# Task 03
# Part 1: Print numbers from 1 to 10 using while loop
print("Numbers from 1 to 10:")
i = 1
while i <= 10:
    print(i)
    i = i + 1

# Part 2: Print even numbers between 1 and 20
print("\nEven numbers between 1 and 20:")
i = 2
while i <= 20:
    print(i)
    i = i + 2
# Task:04
num = int(input("Enter a number: "))

sum_of_digits = 0
temp = num

while temp > 0:
    digit = temp % 10
    sum_of_digits = sum_of_digits + digit
    temp = temp // 10

if num % sum_of_digits == 0:
    print(num, "is a Harshad Number.")
else:
    print(num, "is not a Harshad Number.")
