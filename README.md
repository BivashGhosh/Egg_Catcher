# Egg_Catcher
Eggs Catcher is a classic game where the goal is to catch as many eggs as possible. In this game, every egg you catch will increase your score and if you miss 3 eggs you will lose the game. In this article, I will walk you through how to create an egg catcher game using Python.


How To Create An Egg Catcher Game using Python?

To create an eggs catcher game using Python, your first step will be to design a floor, basket, and eggs. Once your game starts, the eggs will gradually 
move across the floor, which will create an animation indicating that the eggs are falling. Then with the help of loops, we can constantly check that 
the eggs have been caught in the basket or have touched the ground. When the egg is caught or dropped, it will be an end of an event, so here the egg 
will be removed and the game has to adjust the score by increasing the score if the egg was caught in the basket or by decreasing your one life if the egg 
has touched the ground.

To create an egg catcher game using Python, we need to use three different loops:

1.One to create new eggs.
2.Another to check if the catcher has caught an egg.
3.And the third loop to move eggs and to check if the eggs touched the ground

To create this game, will be using three Python modules:

itertools: to change the colours of the falling eggs.
random: to make the eggs appear at random positions.
Tkinter: to animate the game on the screen.
