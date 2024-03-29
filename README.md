# Group-35 (Project)

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
Generate a (5x5 / 9x9 / 16x16) board with selected number of "mines" for each game. The "mines" will be randomly generated by the programme. The target of player is to clear the "mines" of the board without detonating the "mines".

## Game Rules (Updated)
1. Before the start of the game, player need to input the difficulty of the game, which decided the size of board, number of "mines".
2. Player can only input one position (in row and column) for each movement.
3. For each movement, if the selected unit is not "mine", there will be hints provided, telling the player how many "mines" around the cleared spot.
4. If all the unit are cleared and the "mines" are not detonated, the game will finish and the player will win the game.

## Features and Coding Requirements (Updated)
* 1: Generation of random game sets or events
    * The position of the "mines" is randomly generated in Mines_implementation function in mines.cpp file
    * The generation of mines position involved rand() in <stdlib.h> library

* 2: Data structures for storing game status
    * The game will use 2D arrays for storing the game status, such as the board on screen, minesboard and mines position
    * The array will be changed and update after the player input their row and colum

* 3: Dynamic memory management
    * Dynamic array is used to facilitate the file output
    
* 4: File input/output (e.g., for loading/saving game status)
    * There are graphic input to the terminal in the beginning and ending of game
    * The answer of the minesweeper will be output as answer.txt for player to cheat if needed
    
* 5: Program codes in multiple files
    * The mines.cpp contains the function to implement "mines", the main.cpp contains all the left functions of the game.
    * Use makefile to compile the program from the source codes (main.cpp and mines.cpp).\
    
## User Command
1. Download the whole folder
2. Open terminal in the file
3. Type "make" enter
4. Type "./main" enter
5. Play the game

*Testing Server: Academy 11 Server

*p.s. The sample input/output files are used for reference only, as the game involved random generation of mines location, output may not be the same.
