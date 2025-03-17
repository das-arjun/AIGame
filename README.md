#GPT's Explanation:
Random Number Generation:

We use rand() to generate a random number and srand() to seed the random number generator with the current time (using time(0)).\
The random number is generated between 1 and 100 (rand() % 100 + 1).\
Game Loop:
\
The game continues in a loop where the player is asked to input a guess.\
If the guess is too low or too high, the program gives feedback to the player.\
When the player guesses correctly, the program congratulates them and displays the number of attempts.\
Input and Output:
\
We use cin to take user input and cout to display messages to the user.\
How to compile and run:\
Save the code to a file, for example guessing_game.cpp.
\
Open a terminal (or command prompt) and navigate to the directory where the file is saved.\
\
Compile the code using a C++ compiler.
