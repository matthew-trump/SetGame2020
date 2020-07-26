# SetGame2020
Swift UI version of [game of SET](https://en.wikipedia.org/wiki/Set_(card_game)) as specified in [Assignment 3 of Stanford CS193P Spring 2020](https://cs193p.sites.stanford.edu/sites/g/files/sbiybj16636/files/media/file/assignment_3.pdf)

## Objective 

The goal of this assignment is to give you an opportunity to create your first app
completely from scratch by yourself. It is similar enough to the first two assignments
that you should be able to find your bearings, but different enough to give you the full
experience! 

## Required Tasks

1. Implement a game of solo (i.e. one player) Set. 
```diff 
+ Status: done
```
2. When your game is run for the very first time, there should briefly be no cards
showing, but as soon as it appears, it should immediately deal 12 cards by having them
“fly in” from random off-screen locations. 
```diff 
+ Status: done
```

3. . As the game play progresses, use all the real estate on the screen in an efficient
manner. Cards should get smaller (or larger) as more (or fewer) appear on-screen at
the same time, while always using as much space as is available and still being “nicely
arranged”. All changes to locations
and/or sizes of cards must be animated. 
```diff 
+ Status: done
```

4. Cards can have any aspect ratio you like, but they must all have the same aspect ratio at
all times (no matter their size and no matter how many are on screen at the same
time). In other words, cards can be appearing to the user to get larger and smaller as
the game goes on, but the cards cannot be “stretching” into different aspect ratios as
the game is played. 
```diff 
+ Status: done
```

5. The symbols on cards should be proportional to the size of the card (i.e. large cards
should have large symbols and smaller cards should have smaller symbols). 
```diff 
+ Status: done
```

6. Users must be able to select up to 3 cards by touching on them in an attempt to make
a Set (i.e. 3 cards which match, per the rules of Set). It must be clearly visible to the
user which cards have been selected so far. 
```diff 
+ Status: done
```
7. After 3 cards have been selected, you must indicate whether those 3 cards are a match
or mismatch. You can show this any way you want (colors, borders, backgrounds,
animation, whatever). Anytime there are 3 cards currently selected, it must be clear to
the user whether they are a match or not (and the cards involved in a non-matching
trio must look different than the cards look when there are only 1 or 2 cards in the
selection). 
```diff 
+ Status: done
```




