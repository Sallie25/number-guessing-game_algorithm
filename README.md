# **Project Title** : ### Number Guessing Game

##  **Description**
This is a simple number guessing game written as an algorithm using pseudocode.  
The program randomly chooses a secret number between **1 and 10**.  
The user must guess the number, and the program provides hints if the guess is **too high** or **too low**, repeating until the user guesses correctly.

---

## **Algorithm as a pseudocode**

START

1. Generate a random number between 1 and 10 and store it as secretNumber using the random module perhaps.

2. Display "Guess a number between 1 and 10"

3. REPEAT
      a. Get user input and store it as userGuess.
      b. IF userGuess < secretNumber THEN
             Display "Too low! Try again."
         ELSE IF userGuess > secretNumber THEN
             Display "Too high! Try again."
         ELSE
             Display "Correct! You guessed the correct number!"
             EXIT LOOP
   UNTIL userGuess equals secretNumber

4. Display "Game Over."

END

---

##  **project Details**
1. Start the program.
2. Generate a random number between 1 and 10.
3. Ask the user to guess the number.
4. Use a **loop** to:
   - Check if the guess is **too low**, **too high**, or **correct**.
   - Continue prompting the user until the correct number is guessed.
5. When the guess is correct, display a **congratulatory message** and end the program.

---
## Project Author
**Akpan Salome Gabriel**

## Peer Reviewer
**Abiola Okubadejo**




