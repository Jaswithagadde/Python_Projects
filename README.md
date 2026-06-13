# Number Guessing Game 🎯

A simple Python-based Number Guessing Game where the computer randomly selects a number between **1 and 50**, and the player must guess it within a limited number of attempts.

## Features

* Random number generation using Python's `random` module
* Two difficulty levels:

  * **Easy**: 10 attempts
  * **Hard**: 5 attempts
* Feedback after each guess:

  * Too High
  * Too Low
  * Correct Guess
* Input validation to handle non-numeric inputs
* Displays remaining attempts after each guess

## How It Works

1. The computer generates a random number between **1 and 50**.
2. The player selects a difficulty level:

   * Easy → 10 attempts
   * Hard → 5 attempts
3. The player enters guesses.
4. The program provides hints whether the guess is too high or too low.
5. The game continues until:

   * The player guesses the correct number, or
   * The player runs out of attempts.

## Technologies Used

* Python 3
* Random Module

## Project Structure

```text
number_guessing_game.py
README.md
```

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/number-guessing-game.git
```

2. Navigate to the project directory:

```bash
cd number-guessing-game
```

3. Run the program:

```bash
python number_guessing_game.py
```

## Sample Output

```text
Let me think of a number between 1 to 50

Choose level of difficulty(easy or hard) : easy

You have 10 attempts remaining to guess the number

Make a guess : 25

Your answer was too low

Guess again

You have 9 attempts remaining to guess the number

Make a guess : 37

You got it! The answer was 37
```

## Learning Concepts

This project helps beginners understand:

* Functions
* Conditional Statements (`if-else`)
* Loops (`while`)
* Exception Handling (`try-except`)
* User Input
* Random Number Generation
* Basic Game Logic

## Future Improvements

* Add replay functionality
* Add score tracking
* Add multiple difficulty levels
* Create a graphical user interface (GUI)
* Store high scores in a file

⭐ If you found this project useful, consider giving it a star on GitHub!
