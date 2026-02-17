# Sum-of-Digits-of-an-Integer
sum = 0
number = int(input("Enter an integer: "))
while number != 0:
    digit = number % 10
    sum += digit
    number = number // 10
print("Sum of digits is:", sum)

OUTPUT:
Enter an integer: 1234
Sum of digits is: 10
