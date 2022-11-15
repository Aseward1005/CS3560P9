# CS3560P9
The objective of this project was to build a simple program in the Jack language
This solves project 9 of Nand2Tetris

My idea was to create a sort of maze game.

There is a mesh grid that wraps around both sides. Player 1 is the goalpost and moves to find a hiding spot.

Player 2 then navigates through the grid and attempts to find player 1.

This compiled, but ran out of memory before I was able to see if the game actually worked.
I believe there is some memory optimization to be done, namely deallocation, for this to actually work.

While I am doing this for a class, and turning this in is likely okay (and this is due very soon), it is bothering me that this seemingly simple game runs out of memory and I SHOULD be able to play Tetris(a seemingly more complicated game) with this.
It leads me to believe I am doing something wrong in my code, so I will likely be going back through this to see if deallocation truly is the answer here.

It may also be that my implementation of the board is just too memory intensive, thinking back on where it crashed, this could also make sense, as each node has 5 fields, and my initial test was with a 4x4 board, which has 16 nodes. More investigation needs to be done.
