# Hangman Game

This project is a simple command-line Hangman game implemented in Python. The game randomly selects a word from a predefined list, and the player has to guess the word one letter at a time. The player has a limited number of incorrect guesses before the game is over.

## Features

- Randomly selects a word from a predefined list of words.
- Displays the current state of the word with underscores for unguessed letters.
- Draws the hangman figure as incorrect guesses are made.
- Ends the game when the player either guesses the word correctly or exhausts the allowed number of incorrect guesses.

## Prerequisites

- Python 3.x

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/hangman.git
    ```

2. Navigate to the project directory:
    ```bash
    cd hangman
    ```

## Usage

1. Run the Hangman game:
    ```bash
    python main.py
    ```

2. Follow the prompts in the terminal to guess letters and try to figure out the word.

## How to Play

- The game will display a series of underscores representing the letters of the word to be guessed.
- You will be prompted to guess a letter.
- If the guessed letter is in the word, it will be revealed in its correct position(s).
- If the guessed letter is not in the word, a part of the hangman figure will be drawn.
- The game continues until you either guess the word correctly or make six incorrect guesses.

## Example

![Screenshot 2024-07-06 215233-win](https://github.com/sakapanchu/CodeAlpha_Hangman_Game/assets/117504870/9b41f071-56da-4a3e-a49c-a622b10bc5a3)
![Screenshot 2024-07-06 214818 not correct](https://github.com/sakapanchu/CodeAlpha_Hangman_Game/assets/117504870/46434a1c-b922-4a25-8afa-543093e8859f)
