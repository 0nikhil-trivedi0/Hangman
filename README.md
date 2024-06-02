# Hangman Game

This repository contains a Python implementation of the classic Hangman game. In this game, players attempt to guess a hidden word by suggesting letters within a limited number of attempts. Incorrect guesses result in the gradual drawing of a hangman.

## Files

- `main.py`: Contains the main game logic.
- `hangman_art.py`: Contains ASCII art for the hangman stages and the game logo.
- `hangman_words.py`: Contains a list of words used in the game.

## Features

- Word selection from a predefined list.
- User-friendly interface for guessing letters.
- Visual representation of the hangman's progress through ASCII art.
- Win and lose conditions with appropriate end messages.

## Requirements

- Python 3.x

## Installation

1. Clone the repository to your local machine:

    ```sh
    git clone https://github.com/your-username/hangman-game.git
    cd hangman-game
    ```

2. Run the game:

    ```sh
    python main.py
    ```

## Usage

Run `main.py` to start the game. Follow the on-screen prompts to guess letters and try to reveal the hidden word before running out of attempts.

### Example

```sh
$ python main.py
Welcome to Hangman!
_ _ _ _ _
Guess a letter: a
Incorrect! You have 5 attempts left.
_ _ _ _ _

