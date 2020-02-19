### Step 1

You're writing a program (function) to play a variety of BlackJack.

In general, __given two numbers__, ```score``` and ```next_card```, __return their sum__.

If the sum is greater than ```21```, then return ```-1```, unless the second number is ```11```(Ace Card). In such a case, the ```11``` should be 'converted' to a ```1``` to prevent the sum from being exceeded.

For example
 - given a ```9``` and ```4``` as input, the result should be ```13```
 - given a ```20``` and ```2``` as input, the result should be ```-1```
 - given a ```11``` and ```13``` as input, the ```11``` __should not__ be 'converted' into a ```1```, so the total sum will be ```24```- the result should be ```-1```
 - given a ```13``` and ```11``` as input, the ```11``` should be 'converted' into a ```1```, so the result will be ```14```


##### [Done? Move to next step](step2.md)
