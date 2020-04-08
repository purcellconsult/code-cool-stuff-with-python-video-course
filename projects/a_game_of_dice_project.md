# Project: A Game of Dice. Humans vs Randomization

An object that involves heavy randomization is a dice. This cubic device has a wide array of application such as tabletop games, board games, and of course gambling. A dice can easily be modeled computationally through the use of a _random_ module. Python has a built in one for this which is conveniently named _random_. We’ll create a simple yet elegant game that involved randomization called _A Game of Dice._

The user will start with a bank account of $1000 and can keep making wagers on which number the dice will roll on. If the dice falls on the number that the user guesses, then the user gets the money that they wagered, and vice-versa. The game play will continue until the user runs out of money or exits from the game. This is a truly simple game that displays the beauty and the volatile nature of randomness.

## Script Hint

Let’s breakdown the logic:

-   Who goes first? The first question is how to determine which player goes first, the human or the computer? One way is to simulate a coin flip of heads or tails. Both players are allowed to pick which side of the coin they want. If both players both pick the correct side then this process should be repeated until there’s a single winner.
    
-   How much money will each player start with? What happens when some edge cases arise like a player betting more money than they have, or enters an invalid input like a string?
    
-   What’s the minimum and maximum amount of rounds allowed?
    
-   What happens when the player has no more money to bet?