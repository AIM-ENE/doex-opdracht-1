# DOEX WEEK 1 

## Casus: Mastermind

Aangepast op basis van beschrijvingen op https://nl.wikipedia.org/wiki/Mastermind en https://en.wikipedia.org/wiki/Mastermind_(board_game).


Mastermind or Master Mind is a code-breaking game for two players

The game is played using:

- a decoding board, with twelve rows each containing four large holes next to a square of four small holes. At the low end of the board there is an additional row with four large holes, but no square of small holes. This row is covered by a shield.
- code pegs of six different colors (blue, green, orange, purple, red, yellow), with round heads, which will be placed in the large holes on the board
- key pegs, some black and some white, which are flat-headed and smaller than the code pegs. They will be placed in the small holes on the board.

One player becomes the codemaker, the other the codebreaker.

The codemaker starts by choosing a pattern that the codebreaker needs to guess. 

The codemaker places four code pegs in the row covered by the shield, to hide the pattern from the codebreaker. The pattern cannot contain blanks and/or duplicates.

Each turn, the codebreaker makes a guess at the pattern and the codemaker gives feedback on the guess.

A guess is made by placing four code pegs in top most empty row on the decoding board. 

Feedback is given by by placing from zero to four key pegs in the small holes of the row with the guess. A colored key peg is placed for each code peg from the guess which is correct in both color and position. A white key peg indicates the existence of a correct color code peg placed in the wrong position.

If the codebreaker guesses the pattern, in both order and color, within twelve turns, the codebreaker wins, otherwise the codemaker wins. 