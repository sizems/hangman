# Hangman

I created this game for a coding bootcamp using JavaScript, jQuery, HTML, and CSS. Players can enter their own word (for 2-player games) or have a word selected for them at random. The game can be played at https://sfwinters.github.io.
The random word generator is supplied via the node module "rword," which can be found at https://www.npmjs.com/package/rword.

The random generator will not include spaces or special characters, so those will be counted as incorrect guesses.
Win condition: Player correctly guesses all letters and completes the word.
Lose condition: Player uses all available guesses without completing the word. Hangman character is added one incorrect guess at a time.
