# bulls-and-cows
Guessing game application.

Guessing game application that creates a secret code (random text string) based on user input that can 
consist of numbers '0-9' and letters 
'a-z'. 

The user chooses the length of the secret code, and how many different symbols it can consist of. The
secret code can not contain duplicates.
When the code is created, the user needs to try to guess what it is. 

If the user inputs a code of 4 in length and with 12 different character symbols, the guessing reference 
will be -> '0-9, a-b' (a total of 12 symbols). 

For every guess, the application will print 'bull' (correct symbol at correct location), and/or 'cow' 
(correct symbol at wrong location), followed by the number of each correct guess.

Example: secret code- > '9374'

Turn 1:
user input -> 'a34n'.
output -> "Grade: 1 bull and 1 cow". 

Turn 2:
user input -> 'a3n4'.
output -> "Grade: 2 bulls". 

Turn 3:
user input -> '9364'.
output -> "Grade: 3 bulls and 1 cow". 

Turn 4:
user input -> '9374'.
output -> "Grade: 4 bulls". 
"Congratulations! You guessed the secret code."
