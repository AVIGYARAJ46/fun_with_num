This Python script implements a simple number guessing game where the player tries to guess a secret number between 1 and 100.

How it Works
Generate Random Number Function:
The getRandomNumber() function generates a random integer between 1 and 100 using the randrange() function from the random module.

Give Hint Function:
The giveHint() function provides a hint to the player based on their guess. It returns:
"Cold" if the guess is more than 10 units away from the secret number.
"Hot" if the guess is within 10 units of the secret number.
"Right" if the guess is correct.

Run Guess Function:
The runGuess() function is the main function of the game. It generates a secret number using getRandomNumber() and then repeatedly prompts the user to guess the number until they guess it correctly.
After each guess, it provides a hint using the giveHint() function.

Main Execution:
The __name__ == '__main__' block ensures that the runGuess() function is executed when the script is run directly.




#Usage
Run the script and follow the prompts to guess the secret number.
Enter a number between 1 and 100 when prompted.
