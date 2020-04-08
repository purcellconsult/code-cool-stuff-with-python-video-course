

# Text Based Calculator

In this project you'll build a text based calculator that emulates the functionality of a scientific calculator. Below are the features that should be emulated:
addition

 - subtraction 
 - multiplication 
 - division 
 - modulus 
 - square root 
 - exponential
 - basic trigonometry: shows sin(), cos(), tan() results for a number
   entered both in radians and degrees. 
 - logarithm

Since I didn't teach functions yet don't worry about making the code modular. Instead, just get the program to work. Here's some code to get you started:
```python
'''
# addition operation
'''

a1 = float(input('Addition. Enter first number '))
a2 = float(input('Enter second number '))
a3 = a1 + a2

print(a1, '+', a2, '=', a3)
```
    

Also, here's a test case so that you can verify that the code works:

    Addition. Enter first number 10
    Enter second number 10
    10.0 + 10.0 = 20.0
    Subtraction: Enter first number 20
    Enter second number 100
    20.0 - 100.0 = -80.0
    Multiplication: Enter first number 100
    Enter second number 100
    100.0 x 100.0 = 10000.0
    Division: Enter first number 5
    Enter second number 2
    5.0 / 2.0 = 2.5
    Modulus: Enter first number 10
    Enter second number 3
    10.0 % 3.0 = 1.0
    Square root: Enter number to take square root of 9
    √ 9.0 = 3.0
    Exponentiation. Enter a number for the 'base' 10
    Enter the power 3
    10.0 ^ 3 = 1000.0
    Enter number to compute, sin, cos, and tan of 115.5
    0.9025852843498607 ° sine
    0.6734960211850264 r sine
    -0.4305110968082949 ° cosine
    -0.7391908477842096 r cosine
    -2.0965435990881756 ° tangent
    -0.9111260281480631 r tangent
    Logarithm. Enter the value of x 9
    Enter the base 2
    log base 2.0 of 9.0 = 3.1699250014423126


Once done, name the program *py_text_calculator.py* and upload to your GitHub account. Congrats on taking steps to improving your python programming skills!


-------------------


## The Secret Number
    
This is a simple number guessing game. The purpose of this game is to guess a number within the range of 1-100. Depending on the mode the user selects the program will execute two separate branches.

The first option allows the user to play the game an unlimited number of times until the correct guess is received. The second option is more challenging. If selected the user will be given an arbitrarily number of chances within the range of 1-10 to guess the secret number.

During each guess in both branches, the user should be given feedback on their guess. The program should tell if their guess is less than, greater than, or equal to the secret number. If it’s equal then the program terminates and the following is printed:


The secret numbers

-   Number of tries

-   Max number guessed

-   Min number guessed

-   Summation of all the numbers

-   The average of all of the numbers

    
If the user doesn’t guess the secret number within the allocated number of chances, then the above stats will still be displayed at the end. Make sure to check for edge cases and terminate the program if they’re triggered. Here’s some sample input/output from the program:

  

### Sample Input/Output #1:
    

     Do you want unlimited tries? Enter 'y' or 'n' y
    
    Enter a number in the range of 1-100 10
    
    10 is less than the secret number
    
    Enter a number in the range of 1-100 20
    
    20 is less than the secret number
    
    Enter a number in the range of 1-100 30
    
    30 is less than the secret number
    
    Enter a number in the range of 1-100 40
    
    40 is less than the secret number
    
    Enter a number in the range of 1-100 50
    
    50 is less than the secret number
    
    Enter a number in the range of 1-100 60
    
    60 is less than the secret number
    
    Enter a number in the range of 1-100 70
    
    70 is less than the secret number
    
    Enter a number in the range of 1-100 80
    
    80 is less than the secret number
    
    Enter a number in the range of 1-100 90
    
    90 is bigger than the secret number
    
    Enter a number in the range of 1-100 85
    
    85 is bigger than the secret number
    
    Enter a number in the range of 1-100 84
    
    84 is bigger than the secret number
    
    Enter a number in the range of 1-100 83
    
    83 is bigger than the secret number
    
    Enter a number in the range of 1-100 82
    
    82 is bigger than the secret number
    
    Enter a number in the range of 1-100 81
    
    81 is the correct answer
    
    Number of tries = 14
    
    Max number you guessed = 90
    
    Min number you guessed = 10
    
    Summation of numbers = 865
    
    The average of numbers = 61.79
