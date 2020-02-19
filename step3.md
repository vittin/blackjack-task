### Step 3


You're writing a program (function) to count a player (human) score.

In general, given input equal to ```y```, hold a player ```score``` (at start it should be equal to 0) and draw a `random_card` by calling the program from _step 2_

Then, __put the ```score``` and ```random_card``` into the BlackJack program__ from _step1_. Then, use the output from that program to set a new player ```score```. 

In the case that one of the following is true:
 * program output is ```-1```,
 * program output is ```21```,
 * player input is not ```y```,
 
you should display the player ```score``` and return it.