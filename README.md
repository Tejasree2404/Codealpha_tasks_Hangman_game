Hangman Game
This repository contains a Python implementation of the classic Hangman word-guessing game. In this game, the player attempts to guess a hidden word by guessing individual letters. The player has a limited number of incorrect guesses before the game ends.

Features
A random word is selected from a predefined list for each game.
The player can guess letters, and the word's current state is displayed after each guess.
Incorrect guesses result in a visual representation of a hangman, which progresses as the player makes mistakes.
The game ends when the player correctly guesses the word or uses all their guesses.
Game Rules
The player can guess one letter at a time.
If the letter is correct, it is revealed in the word.
If the letter is incorrect, a part of the hangman is drawn.
The player wins if they guess the entire word before the hangman is fully drawn.
The player loses if they exceed 6 incorrect guesses.
Getting Started
Prerequisites
Python 3.x must be installed on your machine. You can download it from python.org.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/hangman-game.git
Navigate into the project directory:

bash
Copy code
cd hangman-game
Run the game:

bash
Copy code
python hangman.py
How to Play
After running the game, a word is randomly selected, and the number of letters is displayed.
The player will be prompted to guess a letter.
Correct guesses will reveal the letter in the word, while incorrect guesses will draw parts of the hangman.
The player wins by guessing all the letters in the word before making 6 incorrect guesses.
Example
bash
Copy code
Welcome to Hangman!
The word has 7 letters.

_ _ _ _ _ _ _ 
Incorrect guesses left: 6
Guessed letters: 

Guess a letter: p
Good guess! 'p' is in the word.

p _ _ _ _ _ _ 
Incorrect guesses left: 6
Guessed letters: p
Customization
You can modify the list of possible words by editing the words list in the hangman.py file:
python
Copy code
words = ['python', 'developer', 'hangman', 'programming', 'algorithm', 'function', 'variable']
Add or remove words as desired.
