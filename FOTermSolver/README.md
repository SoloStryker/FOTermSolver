# FOTermSolver
Solve Fallout terminal hacking minigame

NOTE: this project is for educational purposes.

In Fallout as part of the hacking minigame you are presented with a screen consisting mainly of symbols with up to 20 dictionary words mixed in. 
The dictionary words will be all caps and with length and quantity determined by the 'difficulty' of the game, and the amount by the player's skill
You have four attmepts to find the word that will solve and unlock the terminal, the other words are 'duds' that will remove the word and one of your attempts.
Expending all of your attempts without finding the answer fails the minigame, locking out the terminal. Failing or exiting the minigame resets the board.
Among the jumbled symbols are various patterns that give random effects, using those will be partly outside the scope of this project at this time save for allowing 
more than 4 entries in this project, and allowing answers to be marked as 'dud'.
When an incorrect word is chosen, as long as an attempt remains, a number is displayed indicating the number of correct characters in the correct place. The
Correct answer will always match that number of characters with the attempt, no more or less.

The initial design plan of this project is to provide a text field where the user can type in all of the words given in a screen. Then the user can choose a
previously entered word and assign it the match value given from the minigame. Using this the program will filter the remaining words to possible matches, refining
as more words from the list are marked. Additionally, words can be manually marked as 'dud' if given so by the game.

At some point I'll find and solve a few terminals in game to populate test and sample data.

An example list (from a GIS screencap with two attempts made)
CONFIRM
ROAMING
FARMING 4/7 Correct
GAINING
HEARING
MANKIND 2/7 Correct
MORNING
HEALING
LEAVING
CONSIST
JESSICA
HOUSING
STERILE
GETTING
TACTICS
ENGLISH
PACKING
SELLING
FENCING
KEDRICK