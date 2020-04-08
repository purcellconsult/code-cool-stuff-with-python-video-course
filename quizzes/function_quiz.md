# Function Quiz in Python

1) Create a function call `max_number`  the function allows the user to pass in an arbitrary number of elements the function returns the largest number. Here's some sample input:

    ```
    max_number(1, 3, 1, 2, 9,11, 5, 6, 7, 5, 8) = 11
    max_number(5, 3, 2, 7, 8, 4, 11, 2, 100) = 100
    ```
2) Recursion is a concept in which a function calls itself. This is prevalent in computer graphics and in functional programming languages. Create a function called ``fact`` that takes in a number ``n``, and then computes the factorial of that number. 

	```
	fact_one = fact(5)  
	...
	120

	fact_two = fact(10)
	...
	3628800

	fact_three = fact(50)
	...
	304140932017133780436126081660647688443776415689	60512000000000000
	```

3) Write a function called ``is_palindrome`` that checks if a string is a palindrome. A palindrome is a word that's the same written backwards. Example of palindromes are:

	 - race car 
	 - anna
	 - top spot
	 - noon
	 - wow

	If a string is a palindrome return ``True``, if it doesn't return ``False``. 

4) Write a function called ``reverse_string`` that reverses a string in python. There's one requirement for this. Use a ``while`` loop. 

5) Write a function called ``swap_first_with_last`` that accepts a string of at least length 2, and then swaps the first character with the last one. Make sure the following criterion is meet:

	- Use a ``try/except`` statement to make sure that the string entered is at least size 2. If it's not then an exception should run. 
	
	
	**Sample output**:
	
	```
	swap_first_with_last('hello world')
	...
	dello worlh
	```
	
	```
	swap_first_with_last('he')
	...
	eh
	```
	
	```
	swap_first_with_last('This is awesome!')
	...
	!his is awesomeT
	```
	```
	swap_first_with_last('h')
	...
	ValueError: String length must be >= 2
	```
	```
	swap_first_with_last('')
	...
	ValueError: String length must be >= 2
	```
	
6) Create a function called ``replace_vowels`` that replaces all of the vowels in a string with an asterisk. The function should also give the user the ability to replace all of the vowels with ANY character. Below is sample input/output for the function: 

	```
	replace_vowels('Hello')
	...
	H*ll*
	```
	```
	replace_vowels('Hello World')
	...
	H*ll* W*rld
	```
	```
	replace_vowels('This is a test')
	...
	Th*s *s * t*st
	```
	```	
	replace_vowels('Finito!', '+')
	...
	c
	```
	```
	replace_vowels('abracadabra', '?')
	...
	?br?c?d?br?
	```
