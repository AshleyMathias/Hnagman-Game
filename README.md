# Hnagman-Game
Wanna save a man, Come and try it!!

Hangman Game 🎮
This is a simple command-line Hangman game written in Python. The objective is to guess a randomly selected word by entering one letter at a time. Players must guess the word before running out of lives, represented by the stages of a hangman drawing.

Features
Random word selection from a predefined list.
Visual hangman representation for incorrect guesses.
Tracks the player's remaining lives and alerts them.
Progress display showing correctly guessed letters.
Handles repeated guesses and informs the player if a letter was already guessed.

How to Play
Run the script to start the game.
A word is randomly chosen and represented by underscores (_) corresponding to each letter in the word.
Enter your guesses one letter at a time.
Correct guesses reveal the letter in the word.
Incorrect guesses reduce your lives and display a progressing hangman figure.
The game ends when:
You correctly guess the entire word and win.
You run out of lives, and the hangman figure is fully drawn, signaling game over.

Game Structure
hangman.py: Contains the main logic for the game.
stages: ASCII art list representing the hangman figure for each incorrect guess.
word_list: A collection of sample words for guessing.
