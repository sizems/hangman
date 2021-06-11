# Hangman

Playable game is currently hosted at https://sfwinters.github.io. I used an external package for the random word generator: https://www.npmjs.com/package/rword.

The player has two options: they can enter a word of their choosing (for 2 player games) or they can have a random word selected for them. Once the word is selected, the empty spaces will populate and the player will be given a box to submit their guesses.

The player can guess one letter at a time (the random generator will not provide any phrases or special characters, so those will be marked incorrect). If the letter is present in the word, it will populate on screen (this includes duplicate instances of the letter). Every time a letter is guessed correctly or incorrectly, their remaining guesses will be displayed. 

The player wins the game when all letters are filled in correctly (they can choose to type in the entire word as a guess as well). If the remaining guesses count reaches 0, the player loses.

I wrote this game using vanilla JS, jQuery, and HTML. I used CSS to make elements appear and disappear from the screen as needed. The random word generator was pulled from a node module that I installed containing 370,000 words. 

I wrote this game in July 2020, so the code could stand to be refactored (in particular, removing all the console logs revealing the word). I plan on coming back to this to clean it up at some point.
