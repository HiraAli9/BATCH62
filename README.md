# Python Assignment: #
   # Number Exploration Tool #
## Steps: ##
### 1. Set Up the Input Section ###
   We will create an empty list called number_list[], and ask the user to input their 3 favorite numbers, 
converting each input to an integer.
### Code: ###
number_list = []
for i in range(1, 4):
    num = int(input(f"Enter your {i} favorite number: "))
    number_list.append(num)
### 2. Get the User’s Name ###
   We will prompt the user to input their name, store it in a variable, and use it for personalized greetings.
### Code: ###
name = input("Enter your name: ")
print(f"\nHello, {name}! Let's explore your favorite number:")
### 3. Check for Odd and Even Numbers ###
   We will loop through the list to check if each number is odd or even using the modulus operator.
### Code: ###
for num in number_list:
    if num % 2 == 0:
        print(f"The number {num} is even.")
    else:
        print(f"The number {num} is odd.")
### 4. Calculate the Square of Each Number ###
 We will calculate the square of each number in the list using the exponentiation operator
(**), and display the result.
### Code: ###
for num in number_list: 
   print(f"The number {num} and its square: ({num}, {num ** 2})")
### 5. Calculate the Sum of the Numbers ###
   We will calculate the sum of the three numbers using Python’s sum() function and display the result.
### Code: ###
sum_numbers = sum(number_list)
print(f"\nHere is the sum of your favorite numbers: {sum_numbers}")
### 6. Check If the Sum Is a Prime Number ###
   We will create a loop to check if the sum is divisible only by 1 and itself to determine if it is a prime number.
### Code: ###
if sum_numbers > 1:
    for i in range(2, sum_numbers):
        if (sum_numbers % i) == 0:
            print(f"Alas! {sum_numbers} is not a prime number")
            break
    else:
        print(f"Wow! {sum_numbers} is a prime number")
else:
    print(f"{sum_numbers} is not a prime number")
### 7. Test the Program ###
  We will run the program with different inputs to ensure it works correctly for all cases.
### Example test input: ###
#Name: Alex  <br>#Numbers: 4, 5, 6  <br>#Output:  <br>#The number 4 is even.  The number 5 is odd. The number 6 is even.  <br>#The number 4 and its square: (4, 16)  <br>#The number 5 and its square: (5, 25)  <br>#The number 6 and its square: (6, 36)  <br>#Sum = 15, not a prime number.
###Pic Example:###
[Sample](https://www.instagram.com/p/CsvUCsEtPbj/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==)




