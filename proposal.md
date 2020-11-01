// NOT FINALIZED //

# Matches and Patches

INTRO TEXT TK

## Game Elements
The game will involve 1 board, 2 players, 64 standard tiles, 128 player tiles, and an interface that will run the game on an internet browser.

### Tiles
The 64 distinct standard tiles will be broken up into 3 categories, each featuring 4 subcategories, which will span across the categories (4 to the power of 3 will yield 64). The three categories will be color, shape, and number. Color's subcategories will be red, blue, yellow, and green. Shape's subcategories will be triangle, square, hexagon, and circle. Number's subcategories will be 1, 2, 3, and 4. As a result, there will be 16 red tiles, 16 triangle tiles, etc. For example, the 16 red tiles will include 4 triangles numbered 1 to 4, along with 4 circles numbered 1 to 4, etc.

*Some example standard tiles:*
![Blue-Four-Square Card](/images/blue-four-square-card.png)

![Red-One-Circle Card](/images/red-one-circle-card.png)

![Green-Two-Triangle Card](/images/green-two-triangle-card.png)

In addition to the standard tiles, there are 128 non-distinct player tiles. Each player will only have one style of tile, and it will be used to indicate that they have won a particular cell on the board. There are only 128 of them in order to account for the possibility that 1 player may capture all 64 of the board's cells. However, the 128 number is only to account for an analog physical game set (or a hardcoded game); in practice, there will only be 2 pieces, stored as 2 elements in the code.

*The player's tile:*
![Eagle Token](/images/eagle-token.png)

*The opponent's tile:*
![Snake Token](/images/snake-token.png)

### Board
The board for the full game will be an 8-by-8 board, comprising 64 cells, analogous to a chess board. During production, there will also be a smaller, 4-by-4 board, comprising 16 cells. Upon completion, the user may have the option to play using either the large board or the small board. (Note: In both scenarios, the game will use all 64 tiles described above.)

*Large board:*
![Large Board](/images/large-empty-board.png)

*Small board:*
![Small Board](/images/small-empty-board.png)

### Interface
The game will run in the window of an internet browser. The user will play the game by clicking on different parts of the screen. For instance, for each move, they would click on the tile they want to play as well as the cell on the board on which they want to play that tile, then click a submit button to finalize their move. (See below, in the 'Game Play' section, for wireframes of the interface.)

### Players
The game involves 2 players. However, to make it more enjoyable for the user, they will be playing against an AI instead of another user. The user will henceforth be referred to as 'the player,' and the AI will henceforth be reffered to as 'the opponent.'

## Game Rules
### Setup
### First Move
### Subsequent Moves
### Capturing
### Winning
### Potential Conflicts
### Rare Scenarios
### Hierarchy of Match Pairs

## Game Play
### Landing Page
### Slideshow
### Starting the Game
### Playing the Game
### End of Game

## Full Version vs. Partial Version
### Large Board vs. Small Board
### Dumb AI vs. Smart AI

## Coding Concepts
### HTML
### CSS
### JavaScript
#### Arrays
#### Objects
#### Logic
#### Functions
#### Event Listeners
#### Promises

## Plan
### Timeline
### File Structure