# Program Explaination
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

