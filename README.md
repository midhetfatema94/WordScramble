# WordScramble

This project is a game where a word has been picked by the computer and we need to make as many words as possible by rearranging them.

Features are:
* Checks whether the entered string is a word in the dictionary
* Checks whether all the letters belong in the given word
* Checks for repitition of the word

**TODO**
* Disallow answers that are shorter than three letters or are just our start word. For the three-letter check, the easiest thing to do is put a check into isReal() that returns false if the word length is under three letters. For the second part, just compare the start word against their input word and return false if they are the same.
* Add a left bar button item that calls startGame(), so users can restart with a new word whenever they want to.
* Put a text view below the List so you can track and show the player’s score for a given root word. How you calculate score is down to you, but something involving number of words and their letter count would be reasonable.
* Add a Timer to finish a game within the specified time
