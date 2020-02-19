### Step 5

You're writing a program (function) to make a one round play between two players

In general, given two letter input (```cc```, ```cp```, ```pc``` or ````pp```), preapre a game between two players.

The first letter is the first player type, the second letter is the second player type:
* `c` - computer, 
* `p` - player

You should call a corresponding program for player1, and then corresponding program for player2. Both players score should be stored. Then, determine which player wins. To find the winner check which player score is __closer to 21__, but the score __must not be greater than 21__

For example:
* For input ```pc```, you should call program from _step 3_ (player), then program from _step 4_ (computer).
* For input ```pp```, you should call program from _step 3_ twice.
* For input ```cc```, you should call program from _step 4_ twice. Take a note that you should provide `opponent_score` for first computer player, and that score is not existing yet - to resolve that problem you could provide any value between 0 and 21 as a "target" - let's try some values to find the best strategy! ;) 
