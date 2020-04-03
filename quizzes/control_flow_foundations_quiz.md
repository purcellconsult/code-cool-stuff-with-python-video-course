## Control Flow Foundations Quiz

For questions 1-12,  determine what's printed. Assume the following:

> a, b, c = 5, 10, 15

  Answer what's printed. 

**Question # 1**
      
    if (a == 5) == True:  
        print('Bille Jean')  
      
    if (a == 5) is True:  
        print('simpler')  
      
    if (a == 5) == 0 or (a == 5) == 1:  
        print('something has to work')  

  
**Question # 2** 

    if 1:  
        print('To be or not to be')  
      

**Question # 3**

    if 0:  
        print('To not to be')  


**Question # 4**

    if 5:  
        print('Does this execute?')  

**Question # 5**

    if 0:  
        print('I\'m not sure about this one')  

**Question # 6**

    if True and False:  
        print('oops!')  

**Question # 7**

    if True or False:  
        print('Oops!')  

**Question # 8**

    if not False:  
        print('Negation')  

**Question # 9**

    if not not True:  
        print('Kind of silly')  
      

**Question # 10**

    if True and False | True and 1:  
        print('Despacito')  

**Question # 11**

    if a > 0 and a <= 5:  
        print('Between 0 and 5')  

**Question # 12**
  
    if 0 < a <= 5:  
        print('Between 0 and 5')  

For questions *13-16*, assume the following: 

> a, b, c = 5, 10, 15

**Question # 13**

    if a > b:  
        print('a =', a)  
    else:  
        print('b =', b)  

**Question # 14**

    if not a > b:  
        print('ok, a =', a)  

**Question # 15**

    if a in (0, 1, 2, 3, 4, 5):  
        print('It\'s in there somewhere!')  
    else:  
        print('not here')  

**Question # 16**

    if a in (0, 1) and b in (3, 5) or c in (15, 16):  
        print('Bingo!')  
    else:  
        print('No Bingo!')  

**Question # 17**  
  
Use the following code snippet to answer the following questions:

    random_number = randint(-10, 10)  
    print('Random number =', random_number)  
    if random_number < 0:  
        print('Between -10 and -1')  
    elif random_number >= 0 and random_number <= 5:  
        print('Between 0-5')  
    else:  
        print('5-10')

a) Is there anything wrong with the above snippet of code?

b) How would you simplify the chained comparison?  

c) Rewrite this code snippet so that the conditional statements are in different order?

**Question # 18**

Here's one way to check if a number is even or odd:

    secret_num = randint(1, 10)  
    print('secret_num =', secret_num)  
    if secret_num % 2 == 0:  
        print('even')  
    else:  
        print('odd')

Create another solution for testing if a number is even or odd. Hint, use bitwise operators. 

**Question # 19**

Fizz Buzz is a common interview question which tests your knowledge of conditional statements.  However, this question is more of a souped-up version of Fizz Buzz and is called *Fizz-tastic*. Write if/elif statements that satisfy the following:

 - Create a random variable 'fizz_num' that holds any number from 1-100 
 - For multiples of '3' print 'Fizz'   
 - For multiples of '5' print 'Buzz' 
 - For multiples of 2 but NOT 3 print 'deuce'   
 - For multiples of 2 and 5 print 'deuce *****'   
 - For multiples of 3 and 5 print 'FizzBuzz'   
 - For multiples of 2 and 3 print "Fo' Shizzle" 
 - If the number is not a multiple of 3, 5, and 2 print 'Fizzy'   
 - If the number is equal to 1 print 'UNO'   
 - If none of the above is met just print the number

### Sample output  

    1 -> 'UNO' 2 -> 'deuce' 3 -> 'Fizz' 4 -> 'deuce' 5-> 'buzz' 6-> Fo' Shizzle  
    7-> 'Fizzy' 8-> 'deuce' 9-> 'Fizz' 10-> 'deuce *****' 11-> 'Fizzy' 12-> "Fo' Shizzle" 13-> 'Fizzy'  
    14 -> 'deuce' 15 -> 'FizzBuzz' 100 -> 'deuce *****'