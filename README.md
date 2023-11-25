# DIGIT-COUNT

TO GET DIGITS COUNT AS OUTPUT
def count_digits(number):
    # Convert number to string and count the digits
    num_str = str(number)
    digit_count = len(num_str)
    return digit_count

# Input a number from the user
num = int(input("Enter a number: "))

# Calculate the number of digits in the entered number
digits_count = count_digits(num)

# Display the number of digits
print(f"The number of digits in {num} is: {digits_count}")
