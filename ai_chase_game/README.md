# ChessAI-Game
#### An amazing 1P Chess Game.The Artificial Intelligence Algorithm used or Algorithm used for Engine is "NegMax Algorithm".
# 
![](https://i.imgur.com/i95cA0T.jpg)
# 
# 📝 Description
This is a Chess Game with Two variations.
- Player vs Player
- Player vs Computer
## Summary
ChessAI is game in which 1P game works on NegMax algorithm .In this game one can set the variaton he/she want to play.The Difficulty of the game varies from 1 to 4 depending on the PC of user.The difficulty is basically the depth or how much moves Ahead does the AI calculte the possiblities .AI make a move on the basis of Net Score.This score is Calculated by giving a particular value to each piece and on the Position of the piece located at on chess board.Position Score of that square is different for different pieces .As we know all pieces should move towards the center ,so center square are given more points and so on.

This was a short summary of working of chess Game.
### Some Extra Features
* Press z to undo a move.
* Press r to reset the game.


## NegMax Algorithm Flowchart
![](https://i.imgur.com/yTjkm0o.png)
# 🖼 Screenshots
### Board
![](https://i.imgur.com/L44UUgO.png)
### Mid Game
![](https://i.imgur.com/f2UjT5i.png)
### Oposo Move
![](https://i.imgur.com/1q9JGZe.png)
### Castling
![](https://i.imgur.com/JvGsPuY.png)
### All Possible move of a piece
![](https://i.imgur.com/jmwaHWx.png)

# 
# 🤖 Technology Stack
* Python 3.10.5
* pygame 2.1.2
# Resources
* [Python Rescource](https://www.youtube.com/watch?v=RAwntanK4wQ&list=PLwgFb6VsUj_lQTpQKDtLXKXElQychT_2j)
* [Pygame Rescource](https://medium.com/iothincvit/pygame-for-beginners-234da7d3c56f)
* [NegMax Rescource](https://medium.com/@SereneBiologist/the-anatomy-of-a-chess-ai-2087d0d565)
* [Youtube Rescource](https://www.youtube.com/watch?v=EnYui0e73Rs&list=PLBwF487qi8MGU81nDGaeNE1EnNEPYWKY_)

# 🔮Future Work

 - [x] Creating a Board.
 - [x] Positioning Pieces.
 - [x] Legal Piece Movements.
 - [x] En-passant & Castle Moves.
 - [x] Two Player Game.
 - [x] One Player Game using NegMax Algorithm.
  - [ ] Stalemate on 3 repeated moves or 50 moves without capture/pawn advancement.
 - [ ] More Efficient(Depth > 6).
 - [ ] Making App & Website For Playing.


# 
# How to change Difficulty & selection of type of game
If you have a powerful/weak computer, try upping/lowering the depth parameter of the NegMax Algorithm. To do this, navigate to the "chessAI.py" file in the project directory, and locate the Variable name "DEPTH". Once there, you can increase/decrease the range as per your PC.
I Would recommend to Play till Difficulty level or depth 4 , Max to Max 5. As we level increase the Game decome slower and slower.

To select the type of game you should navigate "chessMainBoard.py" line number 50.
#
# 🛠️ Project Setup
1. Install Python:-
  To Install [Python](https://www.geeksforgeeks.org/how-to-install-python-on-windows/).
2. Install Pygame:- 
To install Pygame, open the command prompt and give the command as shown below:

```bash
  pip install pygame
```
```
3. Go to the project directory

```bash
  cd ChessAI-Game
```
4. Start the Game

```bash
   python .\chessMainBoard.py
```

Project Timeline
---
```mermaid
gantt
        Chess Board:a, 2022-08-14, 1w
        Pieces movements: b,after a,10d
        Legal Piece Moves: c, after b, 9d
        Animations & Bug Fixing: d , after c , 10d
        Chess AI: e , 2022-09-17 , 10d

```


