Built a 20x 10 (Columns x Rows) Game Board Area and a Player-Controllable Object with the following
features:
• Upon startup, a stationary player object is placed at the centre of the game board, represented by a special ASCII
character of your own choice.
• The border of the game board is represented by another special character of your own choice.
•Capture the ‘W’, ‘A’, ‘S’, ‘D’ control keys asynchronously as you’ve learned in PPA1, and use the four keys for
commonly known directional control:
o W Upward Direction
o S Downward Direction
o A Leftward Direction
o D Rightward Direction
• Upon the first pressed directional key, the player object must move in the designated direction continuously – 1
unit per game loop cycle. The object must stay on course with the movement direction until the next valid direction
control key is pressed.
o If moving UP or DOWN Only LEFT and RIGHT move command is allowed
o If moving LEFT or RIGHT Only UP and DOWN move command is allowed
• When the player object reaches the board boundary, it must wrap around the border and come in from the
opposite border. For example, if the player reaches the left border, it must come back out from the right border
in the next game loop cycle. Hint: the logic is the same as the marquee display wraparound in PPA1.
• An exit command is deployed to end the program at any time.
• Advanced Features (Above and Beyond Activities)
o Implement a set of keys that can dynamically adjust the overall game speed.
▪ Provide usable instructions and current game speed below the game board.
▪ Choose at max 5 levels of sensible game speed. Don’t run the game too fast to the point that
the player object becomes impossible to control.
