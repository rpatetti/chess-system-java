
# Chess System Java

This is a simple terminal-based chess game implemented in Java. Players can enjoy a game of chess by inputting their moves via the terminal. The game displays the current state of the board, captures pieces for both white and black players, turn count, and the active player's turn.

This Java chess game project, executed in console, was developed as part of Professor Nelio Alves' Java course. The goal is to practice object-oriented programming, exception handling, and layered architecture.

The system validates moves, handles input errors, and applies special rules such as castling, en passant, and pawn promotion.

<img width="1592" height="1701" alt="chess-system-design" src="https://github.com/user-attachments/assets/ffa54158-c826-416f-91ac-e499ed4ec660" />

## Getting Started
### Prerequisites

-   Java JDK (version 8 and higher)
-   Terminal or Command Prompt

### Installation

[](https://github.com/detds/chess-system-java?tab=readme-ov-file#installation)

1.  Clone this repository to your local machine using:
    ```
    $ git clone https://github.com/rpatetti/chess-system-java.git
    ```
2.  Navigate to the  `src`  directory:
    ```
    $ cd chess-system-java/src/
    ```
3.  Compile the Java source files:
    ```
    $ javac application/Program.java
    ```

## How to Play

### Chess Piece Notation

In this chess program, the following piece abbreviations are used:

-   `K`  - King
-   `Q`  - Queen
-   `R`  - Rook
-   `N`  - Knight
-   `B`  - Bishop
-   `P`  - Pawn

These abbreviations represent the different chess pieces on the board.

### Move Notation
Moves are specified by providing the source position and the target position. For example, to move a pawn from a2 to a4, you would input: Source: a2, Target: a4. Make sure to use the correct notation for the source and target positions to execute your moves successfully.

### Gameplay

1.  Open your terminal and navigate to the  `src`  directory.
    
2.  Run the compiled Java program:
    ```
    $ java application.Program 
    ```
3.  The chess board will be displayed.
    
4.  Select the piece you want to move using the following format as an example:
	 ```
    Source: a2
	```
5.  The game will show possible movements for the selected piece.
    
6.  Input the target position for the selected piece using the following format as an example:
    ```
    Target: a4
    ```
    
7.  The game will validate your move, update the board, and display the new state.
    
8.  Continue playing by alternating turns and inputting your moves as described above.

![chess-system-java-demo](https://github.com/user-attachments/assets/596d66b2-e6fa-47ce-8f8c-0a870e858469)

## Features
-   Terminal-based chess game.
-   Interactive gameplay with player input.
-   Displays the current state of the chess board.
-   Keeps track of captures for both white and black players.
-   Shows the turn count and the active player turn.
-   Validates user input and updates the board accordingly.
-   Display of possible movements for selected pieces.
-   Clear and user-friendly interface.
