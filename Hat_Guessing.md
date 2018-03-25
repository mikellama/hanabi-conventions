# The Hat-Guessing Convention Framework

[Floris van Doorn](https://github.com/fpvandoorn/) created [a convention framework called Hat-Guessing](https://github.com/fpvandoorn/hanabi/blob/master/doc_hat_player.md). This is based on the paper [How to Make the Perfect Fireworks Display: Two Strategies for Hanabi](https://www.researchgate.net/publication/297678249_How_to_Make_the_Perfect_Fireworks_Display_Two_Strategies_for_Hanabi) by Christopher Cox, Jessica De Silva, Phillip Deorsey, and Josh Tobin.

This framework is entirely separate from the Hyphen-ated convention framework. This document contains some helpful tools used for humans who are attempting to play with this framework.

## Clue Interpretation Table

| # mod 9 | action    | person clued   | type of clue
| ------- | --------- | -------------- | -------------
| 0       | give clue | 1 player away  | number on newest card
| 1       | play 1    | 1 player away  | color on newest card
| 2       | play 2    | 1 player away  | any clue not touching the newest card
| 3       | play 3    | 2 player away  | number on newest card
| 4       | play 4    | 2 players away | color on newest card
| 5       | discard 1 | 2 players away | any clue not touching the newest card
| 6       | discard 2 | 3 players away | number on newest card
| 7       | discard 3 | 3 players away | color on newest card
| 8       | discard 4 | 3 players away | any clue not touching the newest card

## Modulus Cheat Sheet

| 0 | -18  -9  0  9   18  27
| 1 | -17  -8  1  10  19  28
| 2 | -16  -7  2  11  20  29
| 3 | -15  -6  3  12  21  30
| 4 | -14  -5  4  13  22  31
| 5 | -13  -4  5  14  23  32
| 6 | -12  -3  6  15  24  33
| 7 | -11  -2  7  16  25  34
| 8 | -10  -1  8  17  26  35

