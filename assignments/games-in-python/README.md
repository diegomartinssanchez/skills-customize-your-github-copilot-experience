
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Python Hangman game that practices string handling, loops, conditionals, and user interaction. Students will implement game logic and feedback for a complete word-guessing experience.

## 📝 Tasks

### 🛠️ Build the Hangman Game

#### Description
Write a Hangman game in Python where the program randomly chooses a word and the player guesses letters until they win or run out of lives.

#### Requirements
Completed program should:

- Choose a random word from a predefined list of words.
- Display the current word state with blanks for unguessed letters (for example: `_ a _ _ m a n`).
- Ask the player to guess one letter at a time.
- Track and display incorrect guesses remaining.
- Reveal correctly guessed letters in the word.
- End the game with a win message when the word is fully guessed.
- End the game with a lose message when the player uses all guesses.

### 🛠️ Add Input Validation and Replay

#### Description
Improve the game by validating player input and allowing the player to play again without restarting the program.

#### Requirements
Completed program should:

- Ignore invalid input such as empty entries or more than one character.
- Prevent repeated guesses from counting against the player.
- Ask the player if they want to play again after the game ends.
- Restart the game when the player chooses to continue.
