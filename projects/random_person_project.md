# Project: Random Person Generator

Have you ever seen those online name generators? I have, I’ve used them a couple of times for novels I was writing. Yes, I wrote novels under a pseudonym and occasionally had a difficult time creating names for fictitious characters! It may seem random (no pun) for a software engineer to do that, but there's actually quite a bit of parallels between writing code and writing stories. 

Anyhoo, to prevent from deviating let’s take the functionality of a simple random name generator a step or two further. Let’s write a script that allows us to randomly generate first names, last names, full names, emails, ages, telephone numbers, and email passwords. It will be a fun project to code and showcase!

## Script Hints

Let’s breakdown the script into individual functions so that it’s more modular. Here’s the functions that you can fill-in:

`first_name`: A function that allows us to generate male or female first names. By default we’ll let the program decide on the gendered pronoun.

`last_name`:  A function that allows us to generate surnames.

`full_name`: A function that allows us to generate first and last names. Like the first_name function it can be gendered or we can let the program decide this.

`age`: Generate a random age for the person. We can specify something like 1-100.

`phone_number`: Generate a random 10 digit phone number. For the sake of simplicity  we can decide on the region which in this example are North American phone numbers. The key here is that the first digit can’t be 0 or 1.

`email_password`: We can generate a random email address which uses the random person’s first and last names.

There’s some subtle decisions that we need to make. For one, the randomly generated full name is tied to the email that’s created. Since we’re creating separate functions for the first_name, last_name, and full_name  functions, how can we create the email so that it’s tied to the random name that’s generated? There’s a couple of ways to do this, for one we can call the first_name and last_name functions within the a function that creates the email.

Or, we can do the second approach which is the choice I decided to do which is to include a nested function within the outer function of full_name. Therefore, we can create the full name and within the function give the user the option of creating an email address that uses that randomly generated full name.

If they opt for no then the full name will just be generated, and if they opt for yes then a dictionary with randomly generated name and email will be created. By the way, there’s something else to think about. Where will we get the names from? You don’t have to download a massive file of names, instead I just did a couple of searches online looking for popular male and female names in the USA. 

You’re more than welcome to research popular names in any country you want. You can simply store the names in a list, and then you can use the choice function from the random module to randomly select a name as shown in the code snippet below:

<pre>
>>> from random import choice

>>> female_names = ['Molly', 'Sue', 'Angela']

>>> choice(female_names)

 ...

 'Angela'
 </pre>

To generate a random age is easy, you just need to generate a random number within a realistic interval:

<pre>
>>> from random import randint

>>> [randint(1, 100) for x in range(10)]

 ...

[2, 23, 99, 19, 96, 27, 61, 88, 53, 38]
</pre>

The above is simply a list comprehension that generates a list of 10 random numbers within the range of 1-100. To generate a random password here’s a hint, you should investigate the functions in the string module. You have some useful things available to you  in this module which are shown in the following code snippets:
<pre>
>>> from random import choice

>>> from string import ascii_letters

>>> from string import digits

>>> from string import punctuation

>>> ascii_letters

...

'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'
</pre>

<pre>
>>> digits
...
 '0123456789'
 </pre>

<pre>
>>> punctuation
...

'!"#$%&\'()*+,-./:;<=>?@[\\]^_`{|}~'
</pre>

<pre>
>>> [ascii for ascii in ascii_letters]

 ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']

>>> for x in range(5):
        print(choice(letters))

 ...

H

u

K

u

A
</pre>
