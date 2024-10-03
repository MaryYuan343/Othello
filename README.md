cs3110-final-project
A terminal-based version of the board game Othello, created for our CS 3110 final project.

Authors:

Rahma Abdullah (ra567)
Om Deshmukh (od66)
Arthi Vijayakumar (av439)
Mary Yuan (cy452)
Setup
Refer to INSTALL.txt for installation instructions

Gameplay
Refer to this page for the rules of Othello: https://www.worldothello.org/about/about-othello/othello-rules/official-rules/english

Type command "make othello" to start the othello game

Next, for a singleplayer game, type 's [easy | medium | hard | godmode]' to select an easy, medium, hard, or extreme opponent. For multiplayer, type 'm'. You can also type 'q' to quit, and 'h' for help.

     Example: 's medium'
If playing against a computer, choose a color. You may respond 'b' for black and 'w' for white. Otherwise, the game automatically starts with black, and one player can choose to start the game.

Congrats! You started the game! You can enter moves as (letter, number). Example 'f 5'. The board is printed as a grid. The empty spaces are empty. The black tiles are the circles with black in the center. The white tiles are circles with white in the center. The range of values for row is 1 <= row <= 8 and column is A <= column <= H.

image
If you are playing in mutiplayer mode, you can enter moves for each color one after the other. If you are playing in singleplayer, after you enter the first move, the computer will play its own move and you can enter your next move.

image
Type 'history' at any point in a current game to enter history mode, where you can choose a previous point in the game to return to.

Type 'q' at any point to quit the game. Type 'h' at any point to list all available commands.

When finished, run dune clean in terminal.
