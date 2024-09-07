# MyShelfie

Application developed for the course "Software Engineering" of the Polytechnic of Milan.

## Goal
The main goal of the project is to implement the board game My Shelfie.

## Description
 The project is an implementation of a single-server system that simultaneously manages multiple games of 2-4 players (clients). Each player can join the game using:
- command line interface
- graphical user interface
  
Players can also decide whether to use TCP or RMI as communication techonology during the game. There is also a chat system that can be used by the players during the game both for the graphical user interface and the command line one.  
The application is based on the Model View Controller (MVC) design pattern.

## How to run the application
### Run the server
```bat
java -jar AM11.jar --server
```
### Run a client (command line interface)
```bat
java -jar AM11.jar --client --tui
```
### Run a client (graphical user interface)
```bat
java -jar AM11.jar --client --gui
```
