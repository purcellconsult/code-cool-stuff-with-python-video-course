
1.	Use a loop to generate a list called evens with only even numbers within the range of 1-20.
2.	Use a loop to generate the first 10 factorials and store them in a list. 
3.	Use a loop to generate the square root of the numbers from 1-20 and then add them in a list called `square_roots`. Then, iterate over the list and create a variable called `sum` that adds all of the numbers in `square_root`s together. 
4.	Create a program that prompts the user to enter in 10 numbers. Store all of the numbers in a list called `user_input`. Write the following code: 
	- Display the smallest number in the list.
	 - Display the largest number in the list.
	- Display the summation or total of all the numbers in the list. 
	- Display the average of all the numbers in the list.
5. Create a tuple called `coin` that stores the values 'h' for heads and 't' for tails. The goal of the program is to simulate the flipping of a coin. Answer the following questions: 
	- Create a loop that iterates 1000 times and keeps track of what side the coin landed on. You can use either the `choice` or `randint` function from the `random` module. 
	- Display the total number of times the coin landed on 'h', and the total number of times the coin landed on 't'.
	- Display which side the coin landed on most in the trial. 
6. Modify the above program so that the coin flips an arbitrary number of times. Write a program that does the following:
	- Prompts the user to enter a guess for ‘h’ or ‘t’ to determine what side the coin fell on.
	- Keeps track of the total number of correct guesses the user made. 
	- Tell the user if their guess was correct or incorrect. 
	- Gives the user the option to terminate the simulation by typing the string 'exit'. If they terminate then the program will display the following:
		- The total number of guesses the user made
		- The amount of times the coin landed on heads
		- The amount of times the coin landed on tails 
		- The user percentage of correct guesses

7) Write a program that allows the user to enter an arbitrary number of numbers.  The goal is to use a data structure so that only unique numbers will be stored. Answer the following questions:
	- What data structure should you use and why?
	- Write the code to read in an arbitrary number of user input.
	- Store the input in said data structure with the name `unique.`
	- Display the results.  

8) Use the following dictionary to answer the following questions:

    supply = {
        'currency': {'gold': 100, 'dollars': 300},
        'tools': ['pliers', 'flashlight', 'compass'],
        'backpack': ['bread loaf', 'water', 'book']
    }

- Add key 'silver' and value 100 to currency
- add value 'blanket' to backpack
- Iterate over the dictionary and display all of the values.


9) Below is a dictionary named `phone_book` that contains mappings of names with their corresponding numbers as shown below: 

    phone_book = {
        'dan': '253-832-2812',
        'mike': '263-821-3292',
        'mary': '323-732-9172',
        'jill': '243-821-9372',
        'corporation': ['800-832-2912', '235-263-2721']
    }

Write code snippet that does the following:

Prompt the user to type in a name. Then, iterate through the dictionary and see if the name is in the dictionary.  The program should be case insensitive meaning that dan, Dan, DAN, or even dAn will all validate. You can use the built-in `casefold` method from the string class to handle case insensitivity. If a match is found display the following messages:

•	`the_key` is in the phone book
•	 `the_value`

If no match is found display the message `the_key` is not in the dictionary. `The_key` represents a name in the dictionary, i.e, `mike` or `jill`. `The_value` represents the phone numbers. 


