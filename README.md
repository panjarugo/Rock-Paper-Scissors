Rock, Paper, Scissors Game:

This is a simple game of rock-paper-scissors that allows the user to play against the computer for five rounds.


How to play:

The program will ask the user to choose between rock, paper, or scissors by entering a number (1 for rock, 2 for paper, 3 for scissors).
The computer will randomly select one of the options as well.
The program will compare the user's choice and the computer's choice to determine the winner of the round.
The winner of each round will receive one point.
After five rounds, the program will declare the winner based on the number of points earned. If there is a tie, the game will declare a draw.



Explanation of the code:

The code begins by importing the random module which will be used later to randomly select the computer's choice.
list_forbot is a list of options that the computer will choose from.
A while loop is used to allow the user to play multiple times.
Inside the while loop, the for loop is used to play five rounds.
The user's choice is taken as input by displaying the options using print statements, and converted to the corresponding option name using if-elif statements.
The computer's choice is randomly selected from list_forbot using the random.choice() function.
The program then compares the user's choice and the computer's choice to determine the winner of the round, and keeps track of the number of rounds won by the user and the computer using youwin and computerwin variables.
After five rounds, the program checks the number of rounds won by the user and the computer to declare the winner. If the user wins, it prints a congratulatory message.
Overall, the code is relatively straightforward and uses basic programming concepts such as loops, conditionals, and random number generation. It is an excellent example for beginners to learn about these concepts in practice.
