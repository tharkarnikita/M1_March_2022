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

![SWOT Analysis](https://github.com/AdityaGautam05/LTTS-C-MiniProject/blob/main/images/swot.png)
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
| HR01 | User shall be able to login                              | Techincal | IMPLEMENTED |
| HR02 | Admin shall be able to login                             | Techincal | IMPLEMENTED |
| HR03 | User shall be able to create account.                    | Techincal | IMPLEMENTED |
| HR04 | User shall be able to update existing account            | Techincal | IMPLEMENTED |
| HR05 | User shall be able to perform transactions               | Techincal | IMPLEMENTED |
| HR06 | User shall be able to check details of existing account  | Techincal | IMPLEMENTED |
| HR07 | Admin shall be able to remove existing account           | Techincal | IMPLEMENTED |
| HR08 | Admin shall be able to view customer list                | Technical | IMPLEMENTED |
| HR09 | Logs will be maintained                                  | Scenario  | FUTURE      |
| HR10 | Admin shall be able to perform rollbacks of transactions | Technical | FUTURE      |

## Low level Requirements:

| ID   | Description                                                                                                                                                                    | HLR ID | Status (Implemented/Future) |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | --------------------------- |
| LR01 | (1). New account shall be added by providing all the asked information (2). Id should be unique and validated from persistant file or else new account should not be accepted. | HR03   | IMPLEMENTED                 |
| LR02 | Must be able to login as User.                                                                                                                                                 | HR01   | IMPLEMENTED                 |
| LR03 | Must be able to login as Admin                                                                                                                                                 | HR02   | FUTURE                      |
| LR04 | If user tries to create an existing account then the system doesn't allow                                                                                                      | HR03   | IMPLEMENTED                 |
| LR05 | User can only update an existing account                                                                                                                                       | HR04   | IMPLEMENTED                 |
| LR06 | User needs to enter account number to perform transation, and if the account doesn't exist then it shows 'No record found'                                                     | HR05   | IMPLEMENTED                 |
| LR05 | User shall be able to check details of only existing account using account_number/name, if it doesn't exist then it shows 'No record found'                                    | HR06   | IMPLEMENTED                 |
| LR06 | Admin shall bew able to remove existing account on basis of account number, else 'Record not found'                                                                            | HR07   | IMPLEMENTED                 |
| LR07 | Admin shall be able to view all customer list in tabular format                                                                                                                | HR08   | IMPLEMENTED                 |

