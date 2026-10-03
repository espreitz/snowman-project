# snowman-project
I created a hangman (snowman) game using python.


# Hangman Game
A chatbot-formatted Hangman game with three difficulty levels, two difficulties of word banks, a hint system, and a point system.
##  Features
-Two word banks to choose from: difficult and more difficult (game randomly selects a word from the word bank)
-Game description printed at the beginning
-Three game difficulties that you can choose from: easy, medium, and hard
-Point system that differs based on your game difficulty
-Final guess feature: you can input your final guess before every normal guess, but you can only do so once.

## How It Works
The game picks a word using the random library, then stores that as a variable called "secret_word". It then creates a variable called "hidden_word" that it uses to show what letters have been guessed correctly.
It checks a letter guess against the "secret_word" variable by using asking if the letter appears in the "secret_word" string. If it does, then the code replaces the index of that letter (or letters) in the "hidden_word" variable using a loop and prints hidden_word so that the correct letters have been revealed (while the rest of the hidden letters stay dashes).
The code decides when a player has won or lost by using an if statement: if guesses = 0 and the user still hasn't guessed the secret word, then they lose. Otherwise, they win.
## Challenges I Ran Into
Some challenges I ran into were figuring out how to call functions and return the right variables. I worked through this though, and I ended up just including many of those variables as parameters (which was somewhat unnecessary). I also found some bugs in my code throughout my process, which I either worked through with logic or used google or AI to help me fix. Comments are in the code about what I had trouble with.
## What I'd Improve With More Time
My code is pretty efficient, and there is not much I would work on in the future besides fixing the parameters of some functions, turning final_guessYN into a function, and turning the win/lose statement into a function as well.
Made by Eli Spreitzer — https://github.com/espreitz
