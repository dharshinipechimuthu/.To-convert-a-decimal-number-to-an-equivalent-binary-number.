# .To-convert-a-decimal-number-to-an-equivalent-binary-number.
def decimalToBinary(num):
    """This function converts decimal number
    to binary and prints it"""
    if num > 1:
        decimalToBinary(num // 2)
    print(num % 2, end='')
number = int(input("Enter any decimal number: "))
decimalToBinary(number)

OUTPUT:

Enter any decimal number: 567
1000110111
