# Hangman Game

## Overview:
This is a simple command-line version of the classic Hangman game implemented in Python. The game selects a random word from a predefined list, and the player must guess the word letter by letter. The player has a limited number of attempts to guess the word correctly before they lose the game.

### Features:
1. **Random Word Selection**: The game randomly selects a word from a list of programming languages (e.g., Python, Java, Kotlin, etc.).
2. **Underscore Display**: The word is represented by underscores, with correct guesses revealing the corresponding letters.
3. **Limited Attempts**: The player has 8 attempts to guess the word.
4. **Basic Input Handling**: The game takes letter guesses from the player and provides feedback on whether the guessed letter is in the word.

### How to Play:
1. **Run the Program**:
   - Execute the script, and the game will start by randomly choosing a word from the list.
   
2. **Make Guesses**:
   - Guess one letter at a time by typing it into the command line and pressing Enter.
   - If the guessed letter is in the word, it will be revealed in the corresponding positions.
   - If the guessed letter is not in the word, you lose one of your 8 attempts.

3. **Win or Lose**:
   - If you correctly guess all the letters in the word before running out of attempts, you win.
   - If you run out of attempts before guessing the word, the game ends, and the word is revealed.
