# Group_17
Project CS222
In our Netbean file we have 5 classes.
We started with the Board class: it allows us to set up a playground and to define methods and variables that we will use later. We also had to modify this method as the project progressed.


Then we wanted to start entering our strategy but we realized that it was simpler to create a class containing methods that could be used for more clarity. This is the "Tools" class.
Each method is explained in the code in comments. Those methods allow us to do show more easily our strategy through the code because there is less methods polluted the course of reflection.

Then we could start to realize our strategy (BoardGame class) and the random strategy (Randomstrat class).


The strategy is explained in the code. 

After defining the variables, we start by making a method to make a random movement, then we use this result by adding the condition "create a village if possible". (lines 28-61)
Then we will evaluate all the possibilities of creating a village and evaluate the score obtained each time. We take the biggest difference of scores between me and the others. (lines 66-128)

If no village can be created we will make a move from a source to a destination according to 2 conditions:
- do not add a hut of my color if it is not necessary (ie if there are not all the colors present on the territory) (line 258)
- do not give the opportunity to my opponent to create a village in the next turn (lines 162-200)

The random strategy is very simple. It's just about taking a random source and a random destination matching the source and storing the motion.
Our goal was to confront our two strategies but the code allowing this did not succeed.

We created the "Player" class to simulate the players. We created it for use in another class to fight two strategies but it did not succeed.
