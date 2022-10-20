# Tic-Tac-Toe Game

What passes dull time better than a few games of tic-tac-toe? This application allows you to play the game with ease as it automatically alternates between players ("X" or "O") and determines a winner as it occurs. If no winner is reached by the time each square has been clicked, the board will inform you as to the stalemate. Good luck!

## How To Read and Run Application

To properly appreciate the fun details of this tic-tac-toe game, simply locate the <b>jsx</b>, <b>html</b> and <b>css</b> files to learn more about it's functionality and styling. 

#### <b>./game.jsx</b> 

Note how custome React components like <i> takeTurn</i> allow two people to play the game swiftly by setting the player to the next player name ("X" or "O") after every turn has been made, that is, after a button has been clicked.

A winner is determined when one of the <i>winning combinations</i> within the array "win" aligns with the board combination. Also note that this array is compiled of each square's individual index number, as opposed to the presence of an "X" or "O". This allows for better control of the application. 

## What's next?

Now that the basics of the tic-tac-toe game are done, improvements can be made! This might include an automatic reset and/or lock of the board once a winner is determined to exemplify that the game is over. 

To make things even more fun, we could include some visual displays once there is a winner, such as confetti falling or shaking the board. 
