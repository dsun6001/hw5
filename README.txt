WRITE-UP:
- letter tiles in the player’s “hand” are selected randomly from a data structure with the proper 
distribution of the letters (code!)
(WORKING)

- letter tiles can be dragged-and-dropped onto target Scrabble squares
(WORKING)

- program identifies which letter tile is dropped onto which Scrabble square
(WORKING)

- board includes at least two bonus squares
(WORKING)

- score is tallied correctly, including consideration of bonus square multipliers
(WORKING)

- any number of words can be played until the player wishes to quit or depletes all tiles
(WORKING)

- the board is cleared after each round so that a new word can be played
(WORKING)

- after playing a word, only the number of letter tiles needed to bring the player’s “hand” back 
to 7 tiles are selected

- score is kept for multiple words until the user restart a new game (implement next vs. restart)
(WORKING)

- Tiles can only be dragged from the “rack” to Scrabble board. If the user drop them anywhere 
else, they will be bounced back to the “rack”.
(WORKING)

- Once the tile is placed on the Scrabble board, it can be moved back to the “rack”.
(PARTIALLY WORKING - first try won't work, but second try will work)

- Except for the first letter, all sub-subsequent letters must be placed directly next to or below 
another letter with no space. Else, they will bounce back to the “rack”.
(NOT WORKING)

- user can always restart the game.
(WORKING)