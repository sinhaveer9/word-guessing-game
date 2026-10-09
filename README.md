# Interactive Word Guessing Game

## Overview

Interactive Word Guessing Game is a command-line game I developed using Python to practice fundamental programming concepts such as loops, conditional statements, lists, and user input.

The program randomly selects a word from a predefined collection of 30 words. The player must identify the hidden word by guessing letters while staying within a limit of 10 incorrect guesses.

I created this project to strengthen my understanding of Python and explore how different programming concepts can work together to build an interactive application.

## Technologies Used

- **Python:** Used to develop the game and implement its logic.
- **random module:** A built-in Python module used to select words randomly from the word bank.

The project uses only Python's standard library and does not require any external packages.

## Key Features

- **Random Word Selection:** Each game begins with a randomly selected word from a collection of 30 words.
- **Interactive Gameplay:** Players enter letter guesses through the terminal.
- **Word Progress Tracking:** Correctly guessed letters are revealed in their corresponding positions.
- **Limited Attempts:** Players are allowed up to 10 incorrect guesses before losing the game.
- **Immediate Feedback:** The program informs players whether their guesses are correct or incorrect.
- **Win and Loss Conditions:** The game ends when the player identifies the entire word or runs out of attempts.

## Example Gameplay

The following example demonstrates how the game works when the selected word is "goat".

```text
Current word: _ _ _ _
Guess a letter: g
Great guess!

Current word: g _ _ _
Guess a letter: o
Great guess!

Current word: g o _ _
Guess a letter: a
Great guess!

Current word: g o a _
Guess a letter: t
Great guess!

Congratulations!! You guessed the word: goat
```

The word is selected randomly, so the gameplay will be different depending on the word chosen and the player's guesses.

## How It Works

1. The program stores 30 possible words in a Python list called `word_bank`.
2. The `random.choice()` function selects a word from the list.
3. A second list, `guessedWord`, represents the hidden word using underscores.
4. The player begins with 10 attempts.
5. A `while` loop repeatedly asks the player to guess a letter.
6. If the guess appears in the word, a `for` loop reveals all matching positions.
7. If the guess is incorrect, the number of remaining attempts decreases by one.
8. The game ends when all letters have been revealed or the player has no attempts remaining.

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/sinhaveer9/word-guessing-game.git
```

### 2. Navigate to the project directory

```bash
cd word-guessing-game
```

### 3. Run the program

```bash
python3 word_guessing_game.py
```

The game will start in the terminal and prompt you to guess letters.

No additional libraries need to be installed.

## What I Learned

Developing this project helped me improve my understanding of Python fundamentals through practical implementation.

I learned how to use lists to store and update information, apply loops to manage repeated actions, and use conditional statements to control the flow of a program.

I also gained experience working with user input, generating random selections, and implementing win and loss conditions.

One of the most interesting parts of the project was understanding how individual programming concepts could be combined to create a complete interactive game.

## Author

**Veer Sinha**
