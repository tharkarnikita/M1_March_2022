# Requirements

## Introduction

-   Tic-tac-toe is a simple, two-player game that, if played optimally by both players, will always result in a tie. The game is also called noughts and crosses or Xs and Os.Tic-tac-toe is a game that is traditionally played by being drawn on paper, and it can be played on a computer or on a variety of media. Other games, such as Connect 4, are based on this classic.
-   This topic was chosen as it helps me to understand a structured programming language like C.

## Objective of the system

-   Our project name is Tic-Tac-Toe game. This game is very popular and is fairly simple by itself. It is actually a two player game. In this game, there is a board with n x n squares. In our game, it is 3 x 3 squares. The goal of Tic-Tac-Toe is to be one of the players to get three same symbols in a row - horizontally, vertically or diagonally - on a 3 x 3 grid.
-   The people using it only have to choose what they have to do, and enter the data,everything else is taken care of by the program.

## Features proposed in the current system

-   Two players involved in the game :
-   A player can choose between two symbols with his opponent, usual games use “X”and “O”. If first player choose “X” then the second player  have to play with “O” and vice versa.  A player marks any of the 3x3 squares with his symbol (may be “X” or “O”) and his aim is to create a straight line horizontally or vertically or diagonally with two intensions:

    -   Create a straight line before his opponent to win the game.
    -   Restrict his opponent from creating a straight line first.

-   User mode consists of options:
    -   Enter the position numbers.
        -  player1 enters a postion number
        -  player2 enters a position number
    -    player1 position with X
    -    player2 position with O
    -   View winner 
        -   Shows winner player1 or player2.
        -   Shows GameDraw if there is a tie.
    -   Exit

## SWOT ANALYSIS

![SWOT Analysis]
- Strengths
    -  The game combines aspects of tic-tac-toe which makes it really interesting to play owing to the nature of the rules, it is possible for the player to come up        with multiple strategies to conquer the game
- Weakness
    -  Some of the rules defined are ambiguous and might lead to confusion during game play.
    Only two player can play the game.
- Opportunities
    -  The play board and the number of pieces can be increased giving rise to more complex strategies
    -  The “gobbling” rules can be tweaked around a little bit to make the game simpler(or complex)
- Threats
    -  Software problem

# 3W&#39;s and 1&#39;H

## Who:

-   Players.

## What:

-   An automated program to play X and O game for players to position their marks so that they make a continuous line of three cells vertically, horizontally, or diagonally.

## When:

-   When these tic-tac-toe panels improve hand-eye coordination and encourage better social interaction by better collaborative play.

## How:

-   Effectively organises provides choices of positions to place their X and O respectively in return displays Winner of the game or GameDraw for a tie.

# Detail requirements

## High Level Requirements:

| ID   | Description                                              | Category  | Status      |
| ---- | -------------------------------------------------------- | --------- | ----------- |
| HR01 | User shall be able to access                             | Techincal | IMPLEMENTED |
| HR02 | Player1 shall be able to choose position                 | Techincal | IMPLEMENTED |
| HR03 | Player2 shall be able to choose position                 | Techincal | IMPLEMENTED |
| HR04 | Choices of positions are set respectively                | Techincal | IMPLEMENTED |
| HR05 | User can see the results displayed                       | Techincal | IMPLEMENTED |
| HR06 | Extra grids can be added                                 | Scenario  | FUTURE      |
| HR10 | User shall be able to perform future implementations     | Technical | FUTURE      |

## Low level Requirements:

| ID   | Description                                                                                                                                                                    | HLR ID | Status (Implemented/Future) |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | --------------------------- |
| LR01 | Player1 choice can be given to set in the position for X. 
                 | HR02   | IMPLEMENTED                 |      
| LR02 | Player1 choice can be given to set in the position for O                                                                                                                        | HR03   | IMPLEMENTED                 |
| LR03 | User can see the results displayed                                                                                                                                              | HR04   | IMPLEMENTED                 |
| LR04 | Extra grids can be added                                                 
                 | HR06   | FUTURE                      |

