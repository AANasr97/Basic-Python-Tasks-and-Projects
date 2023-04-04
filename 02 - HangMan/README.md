# Hangman Game

This code is a Python program that implements a simple game called "Hangman". It imports the Python standard library `random` and a list of words from an external file called `words.py` to randomly select a word for the game.

## How to Play

1. Run the Python script `02 - HangMan.ipynb`.
2. The program will randomly select a word from the `words.py` file and display the number of letters in the word as underscores.
3. Guess a letter by typing it in the terminal and pressing `Enter`.
4. If the guessed letter is in the word, the corresponding underscores will be replaced with the letter.
5. If the guessed letter is not in the word, a part of the hangman will be drawn and your remaining lives will be displayed.
6. Keep guessing letters until you either guess the entire word or run out of lives.

## Code Explanation

The code is well-commented, but here's a brief overview of what it does:

- Imports the `random` module and the `words` list from an external file.
- Initializes an empty list called `slots` to store the correctly guessed letters in the word.
- Prompts the user to guess a letter and converts it to lowercase.
- Loops through each character of the randomly selected word and checks if it matches the guessed letter.
- If the guessed letter is in the word, the corresponding underscore in `slots` is replaced with the letter.
- If the guessed letter is not in the word, a part of the hangman is drawn and the remaining lives are displayed.
- If the player guesses all the letters correctly, they win the game. If they run out of lives, they lose the game.


## Requirements

* Python3


## Usage

1. Clone this repository or download the code files.
2. Navigate to the directory containing the code files.
3. Run the script `02 - HangMan.ipynb`.
4. Play the game and enjoy!


### Done By:
#### Ahmed NasrElDin