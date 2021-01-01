# Chess Memory Match
Memory game inspired by memory match for iphone (https://apps.apple.com/ca/app/memory-match-brain-training-memory-games/id1172020731) projet descriptives : create a 2d grid interrface where chess pieces appear on random squares with the number of pieces increasing when sucessfull and decrease when failing lvl.

the biggest part of the projet will be to create the menu interface where the player can personnalise in depth : Parameters to enable customisation on: Board size, Number of pieces on lvl 1, increase/decrease of pieces on lvl success/fail, numbers of diff pieces, time before pieces dissapear. time between disapearance and solution delivery (use lichess.org coding if possible)

## Original README
The program works by having two decks: a visual deck and a hidden one. Upon game start, the visual deck holds the backsides of all the cards, and the hidden deck holds all the card faces. As the user finds matches, the two matching card faces from the hidden deck replace the card backs of the visual deck, thereby making them permanently visual. By the end of the game, the hidden deck has become the visual deck - all card faces are shown. When the user restarts the game, the visual deck is reset to the card backs, and a new, randomized hidden deck is created.

## Credits
* Originally a card game by Nathan Carmine
* Forked from ncarmine/Memory_Match
* python 3.8 and python-pygame (http://pygame.org/).
* Original card images from http://colome.org/ and spliced to make individual cards.
