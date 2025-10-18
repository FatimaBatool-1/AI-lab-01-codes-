# AI-lab-01/02-codes-
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
# Lab :02 codes
# Task:01
sample_list = ['abc', 'xyz', 'aba', '1221', 'xyzzyx', 'aa', '122']

count = 0

for s in sample_list:
    if len(s) >= 2 and s[0] == s[-1]:
        count = count + 1
        
print("Number of strings with same first and last character:", count)
# Task:02
numbers = (1, 2, 4, 2, 6)

sum_result = sum(numbers)

product_result = 1
for n in numbers:
    product_result = product_result * n

print("Sum is:", sum_result)
print("Product is:", product_result)
# Task: 03
numbers = [1, 2, 4, 2, 6]

largest = max(numbers)

print("The largest number in the list is:", largest)
# Task:04
L = [(), (), ('',), ('a', 'b'), (), ('a', 'b', 'c'), (), ('d',)]

# Remove empty tuples
L = [t for t in L if t]

print("Result =", L)
# Task:05
n = int(input("Enter a number: "))

# Create an empty dictionary
result = {}

# Generate dictionary items
for x in range(1, n + 1):
    result[str(x)] = x * x

print(result)
# Task:06
numbers_dict = {
    '0': 'Zero',
    '1': 'One',
    '2': 'Two',
    '3': 'Three',
    '4': 'Four',
    '5': 'Five',
    '6': 'Six',
    '7': 'Seven',
    '8': 'Eight',
    '9': 'Nine'
}

num = input("Enter a number: ")

for digit in num:
    print(numbers_dict[digit], end=" ")
    
