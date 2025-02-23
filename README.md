# Code-Alpha_Task-1
Developed a hangman problem using python for Code Alpha internship.
Overview
This is a simple implementation of the classic Hangman game in Python. In the game, the player has to guess a randomly chosen word by guessing one letter at a time. The player is given a set number of incorrect guesses before losing the game. The game provides feedback on whether the guessed letter is part of the word, and it also shows the partially guessed word as the game progresses.

Features:
Random word selection from a predefined list.
Player guesses one letter at a time.
Display of the word with correctly guessed letters filled in.
Feedback on incorrect guesses with a limited number of attempts.
A game-over condition once the player runs out of guesses or guesses the word correctly.
Play again option after the game ends.
Requirements
To run the game, you need Python 3.x installed on your system.

You can check if you have Python installed by running:


python --version
Installation
Clone the Repository: If this project is hosted on GitHub or any other repository, you can clone it using Git:


git clone <repository_url>
Run the Code:

After cloning or downloading the project, navigate to the project folder in your terminal or command prompt.
Run the Python script:

python hangman.py
How to Play
When the game starts, a random word will be selected.
The player will be prompted to guess a letter.
If the guessed letter is in the word, it will appear in the word's current blank positions.
If the guessed letter is incorrect, the player loses one of their allowed attempts.
The player can keep guessing letters until they either:
Guess all the letters of the word correctly.
Run out of allowed incorrect guesses (the hangman is "fully drawn").
The game ends when one of the above conditions is met, and the player is asked if they want to play again.
