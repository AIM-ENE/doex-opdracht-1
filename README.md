# DOEX WEEK 1 

## Casus: Mastermind

Onderstaande casus beschrijving is een aangepaste variant van de beschrijvingen op [Nederlandse](https://nl.wikipedia.org/wiki/Mastermind) en [Engelse Wikipedia pagina](https://en.wikipedia.org/wiki/Mastermind_(board_game))over dit klassieke bordspel <sup>*</sup>. Deze beschrijving is (bewust) in het Engels, dus dit mag je doorzetten in je model en code uitwerking <sup>*</sup>

<img src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Mastermind.jpg" align="right" width="200">


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

<hr>

### Opmerkingen

<sup>*</sup> Merk op dat we voor deze intro opdracht kozen voor een Engelse beschrijving. Je mag ook Engelse gebruiken voor je *Ubiquitous Language* en code (klasse- en methodenamen etc.). Let wel op dat je per opdracht bewust een keuze maakt, en niet blind voor Engels kiest omdat je programmeertaal 'toevallig' Engelse keywords gebruikte. Binnen Domain Driven Design (DDD) is namelijk een veel aangehangen tandaard om aan te sluiten bij de taal van de organisatie of het domein "to avoid inconsistencies and miscommunication due to translation problems or misunderstandings" (Birkemeijer 2017).

<sup>**</sup> In het kader van 'eat your own dogfood' hieronder ook een nette 'Bronnen' sectie conform de APA richtlijnen, zoals de AIM controlekaart vereist. In dit materiaal gebruiken we verder ook hyperlinks, zeker omdat deze opdracht beschrijvin bedoeld is om online te lezen. Wees in eigen documenten In eigen documenten spaarzaam om (enkel) hyperlinks te gebruiken. Om documenten op zichzelf te laten staan is gebruiken van APA richtlijnen voor belangrijke bronnen ook goed. Spaar wel gebruikte URL's op, zowel van informatie/achtergrond als van code, maar refactor dit naar APA. De onder Bronnen gegeven URL's zijn ook geversioneerd conform onderstaande quote (Caulfield, 2022):

>APA recommends linking to a specific archived version of the Wikipedia article so that the reader can be sure they are accessing the same version.

## Bronnen

- Birkemeyer, S. (7 aug 2017) *Ubiquitous Language in a non-english domain*. Geraadpleegd juni 2023 op [https://www.webfactory.de/blog/ubiquitous-language-in-a-non-english-domain](https://www.webfactory.de/blog/ubiquitous-language-in-a-non-english-domain)
https://www.scribbr.com/citing-sources/how-to-cite-wikipedia/
- Caulfield, J. *How to Cite a Wikipedia Article* (10 juni 2022). Geraadpleegd juni 2023 op https://www.scribbr.com/citing-sources/how-to-cite-wikipedia/
- *Mastermind* In *Wikipedia.* (26 juni 2023) Geraadpleegd juni 2023 op https://nl.wikipedia.org/w/index.php?title=Mastermind&oldid=57756481
- *Mastermind (Board Game)* In *Wikipedia.* (15 dec 2020) Geraadpleegd juni 2023 op https://en.wikipedia.org/w/index.php?title=Mastermind_(board_game)&oldid=1161997709
