# Hangman Game

This is a simple implementation of the classic Hangman game in Python. The objective of the game is to guess a hidden word by suggesting letters. For each incorrect guess, a part of the hangman is drawn. The game continues until the player correctly guesses the word or runs out of lives.

## Prerequisites
To run this game, you need to have Python installed on your computer.

## Getting Started
1. Clone the repository or download the project files to your local machine.
2. Make sure you have the `hangman_art.py` and `hangman_words.py` files in the same directory as the `hangman.py` file.
3. Open a terminal or command prompt and navigate to the project directory.
4. Run the following command to start the game:

```
python hangman.py
```

## How to Play
1. The game will randomly choose a word from the list of words provided.
2. The word will be displayed as a series of blanks, representing each letter.
3. Guess a letter by entering it in the terminal and pressing enter.
4. If the letter is in the word, it will be revealed in the corresponding blank(s).
5. If the letter is not in the word, you will lose a life.
6. The game will continue until you guess the word correctly or run out of lives.
7. The hangman will be drawn progressively with each incorrect guess.
8. If you guess the word correctly, you win. Otherwise, you lose.

## Additional Information
- The hangman artwork is stored in the `hangman_art.py` file, which includes a list of ASCII art images representing the hangman at different stages.
- The list of words for the game is stored in the `hangman_words.py` file. You can add or remove words from the list to customize the game.
- The game starts with 6 lives, meaning you can make up to 6 incorrect guesses before losing.
- To reveal the chosen word for testing purposes, uncomment the line `# print(f'Pssst, the solution is {chosen_word}.')` by removing the '#' at the beginning.

Have fun playing Hangman!


