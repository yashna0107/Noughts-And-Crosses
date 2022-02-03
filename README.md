# Noughts-And-Crosses
 This is classic old noughts and crosses game to play with your friends offline! <br>

The game starts with a small piece of instructional text informing us that we need to choose a side for our starting player to choose the side the want.
When a player chooses a side, the game begins. This removes the instructional text, makes the player buttons non-interactable and enables the game board by making the grid space buttons interactable.  <br>
Game Play allows us to choose any of the grid spaces. The button associated with the grid space asks the Game Controller for the current player’s side and sets the grid space with the appropriate text and then sets itself as non-interactable. As a final act, the grid space button hands control back to the Game Controller to check the winning conditions and if the game is not over, the GameController changes sides and the game continues.  <br>
When the game is over, we change states again into our game over state. Here we display the winning panel and activate the Restart Button. <br>
Selecting the Restart Button sends us back to our starting state and we are waiting to play, with our instructional text and buttons for our player to choose a side.

Future Work includes the follwoing:
Adding music <br>
Multiplayer options
