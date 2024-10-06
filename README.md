
Hangman - Indian Cities Edition
This is a Python-based Hangman Game where players guess letters to form the names of Indian cities. The game includes a classic hangman design and allows players to guess city names letter by letter until either the correct word is guessed or the player runs out of chances.

Features
Random word selection from a list of Indian cities.
Hangman stages: As the player guesses incorrectly, a hangman figure is progressively drawn.
User-friendly prompts: The game notifies the player of valid and invalid inputs, as well as repeated guesses.
Interactive play: The game keeps track of guessed letters and displays the progress of the word with dashes (-) representing unguessed letters.
How to Play
-The game will randomly select a city name from the list of Indian cities stored in the cities.txt file.
-You have 7 chances to guess the city name correctly.
-After each incorrect guess, a part of the hangman figure is drawn.
-If you guess a correct letter, it will be revealed in the city's name.
-You lose if you run out of chances and the full hangman figure is drawn.
-You win if you guess the word correctly before the chances run out.
Installation
Prerequisites
Python 3.x installed on your system.
Steps
Clone the repository:

bash
git clone https://github.com/krishx28/hangman-indian-cities.git
cd hangman-indian-cities
Create a file cities.txt in the root folder of the project. This file should contain a list of Indian cities, separated by spaces, like so:

Delhi Mumbai Kolkata Chennai Bengaluru Hyderabad Ahmedabad Pune Jaipur Lucknow
Run the game: To start the game, run the Python script:

bash
python hangman.py
How to Add More Cities
To add more cities to the game, simply edit the cities.txt file and add new city names separated by spaces. The game will randomly choose a city name from this file during each new game session.

Game Walkthrough
When the game starts, the following is displayed:

vbnet
Welcome to Hangman!
You have 7 chances to guess the word correctly. Let's begin!

------
+----+
|    |
     |
     | 
     |
     |
     |
========
The player then inputs guesses, and the game informs whether the guessed letter is correct or not.

If the player guesses the full city name correctly:

arduino
Congratulations!! You have won!
The word was: MUMBAI
If the player runs out of chances:

lua
Game over! The word was: MUMBAI. Better luck next time!
Contributing
Feel free to open a pull request or create an issue if you encounter any bugs or have suggestions for improvement.

License
This project is licensed under the MIT License - see the LICENSE file for details.
