# Group-35 (Project Proposal)

## Identification of The Team Members
```
* Team_Member_1 
* Github username: Benwong410 
* Name: Wong Hin Chi 
* UID:3035806324
```
```
* Team_Member_2
* Github username: JaeTee211
* Name: Tsang Hing Kwan Jack
* UID:3035782396
```

# Project

## Name of Game
Minesweeper

## Brief Description
Randomly generate a rectangular board with selected number of "mines" for each game. Clear the unit of the board without detonating the "mines".

## Game Rules (Updated)
1. Before the start of the game, player need to input the number of row and column of the board, also the number of "mines".
2. Player can only input one position (in row and column) to be cleared for each movement.
3. For each movement, if the selected unit is not "mine", there will be hints provided, telling the player how many "mines" around the cleared area.
4. If all the unit are cleared and the "mines" are not detonated, the game will finish and the player will win the game.

## Features and Coding Requirements (Updated)
* 1: Generation of random game sets or events
    * The position of the "mines" is randomly generated in Mines_implementation function in mines.cpp file
    * The generation of mines position involved rand() in <stdlib.h> library

* 2: Data structures for storing game status
    * The game will use 2D arrays for storing the game status, such as the board on screen, minesboard and mines position
    * The array will be changed and update after the player input their row and colum

* 3: Dynamic memory management
    * 
    
* 4: File input/output (e.g., for loading/saving game status)
    * There are graphic input to the terminal in the beginning and ending of game
    * The answer of the minesweeper will be output as answer.txt for player to cheat if needed
    
* 5: Program codes in multiple files
    * use makefile to store function in mutiple files (e.g. mines.cpp file)
