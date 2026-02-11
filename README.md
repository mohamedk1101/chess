Documentation of Added Features
1.	Captured Piece Graveyard: Added two side panels (left and right) that display the Unicode symbols of pieces taken during the game. 
2.	Custom Name Input: Implemented a "Naming Phase" at the start where players can enter their names. The game then refers to them by their names 
3.	Classic Black & White Board: Updated the Tailwind classes to set the board squares to a strict bg-black and bg-white theme.
4.	Light Blue Background: Changed the body class to bg-sky-200 to give the page a light blue look.
5.	Undo Functionality: Added an "Undo Move" button that utilizes the game.undo() method from the chess.js library, allowing players to correct accidental moves.
6.	30-Second Move Timer: Built a countdown timer using useEffect and setInterval. It resets to 30 every time the turn changes.
7.	Personalized Winner Announcement: The status header checks for a game-over state and displays the specific player's name who won the match.
8.	Capture Feedback: Added a "Good job!" text notification that appears briefly at the top of the board whenever a player successfully captures an opponent's piece.
9.	New Game Countdown: When "New Game" is pressed, the board resets only after a 3-second visual countdown ($3 \dots 2 \dots 1$) appears on the screen.
10.	Piece Glow Effect: Added a CSS hover state (piece-glow) that applies a white drop-shadow and a slight scale increase to chess pieces when the mouse is over them.
