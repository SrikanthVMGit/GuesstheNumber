# Guess the Number programmed in java 

### Introduction
The program is a number guessing game implemented in Java. It allows the user to guess a randomly generated number between 1 and 100. The user is prompted to enter their guess, and the program provides feedback on whether the guess is too high or too low. The game continues until the user correctly guesses the number. After each successful guess, the program displays the number of tries it took. The user has the option to play again by entering "yes" or exit the game by entering "no".

This game is a simple and interactive way to test your guessing skills and have fun while trying to guess the correct number within a limited number of attempts.

### Program Explaination
* The code begins with importing the necessary classes: Random and Scanner.

* The main method is the entry point of the program.

* A Scanner object named reader is created to read input from the user.

* The variable play is initialized as "yes". This variable controls the game loop and determines if the user wants to play again.

* The program enters a while loop that continues as long as play is equal to "yes".

* Inside the game loop, a random number between 0 and 99 is generated using the Random class and stored in the variable randNum.

* The variables guess and tries are initialized. guess is set to -1 initially to ensure the first guess is not equal to the random number. tries keeps track of the number of attempts.

* Another while loop begins, which continues until the user's guess (guess) matches the random number (randNum).

* Inside the inner loop, the program prompts the user to enter a guess using System.out.print, and reads the input using reader.nextInt().

* After each guess, the program compares the user's guess with the random number using conditional statements (if, else if, else).

* If the guess is correct, the program displays a success message and the number of tries it took. It then asks the user if they want to play again by reading the input and assigning it to the play variable.

* If the guess is too high, the program displays a message indicating that the guess is too high.

* If the guess is too low, the program displays a message indicating that the guess is too low.

* Once the correct number is guessed, the inner loop ends, and the program goes back to the top of the outer loop.

* If the user chooses not to play again by entering "no", the outer loop terminates, and the program ends.

* Finally, the reader is closed to release system resources.

### Conclusion
In conclusion, the provided code implements a simple number guessing game in Java. It prompts the user to guess a randomly generated number between 1 and 100. The program provides feedback on whether the guess is too high or too low and continues until the user correctly guesses the number. After each successful guess, the program displays the number of tries it took. The user has the option to play the game again or exit.

The game demonstrates the usage of basic Java concepts such as loops, conditional statements, user input, and random number generation. It provides an interactive and engaging experience, challenging the player to make educated guesses and improve their guessing skills. It can be further expanded and customized with additional features and enhancements to make it more enjoyable.

Overall, the program showcases a simple but fun game that showcases the capabilities of Java programming and provides an entertaining experience for the users.


