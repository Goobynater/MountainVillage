# MountainVillage
An idea for a mountain-climber game.
It uses the livewires package, a watered-down version of pygame, which can be installed with all the necessary packages here: https://github.com/livewires/python
If I were to refactor it now, I would separate it into different packages so that it is less jumbled into one file.
I would also make better utilization of abstract methods instead of typing stuff out over and over for subclasses.
CONTROLS:
1- builds a house
2- builds a church
3- builds a barracks
4- creates a lumberjack
5- creates a farmer
6- creates a mountain climber
OBJECTIVE:
Get a mountain climber to the top of the mountain without running out of food.
In order to do this, you will need to make a village.
Resources are represented on the left of the screen:
brown- wood
red- food
yellow- gold
white- population
grey- population capacity
Different buildings/units require different levels of resources. In order to create
a mountain climber, you must have a barracks, 50 food, 50 gold, and 50 wood.
Building a church decreases the chances that your mountain climber will die on his journey.

If you run out of money, all of your farmers will stop working because there is nothing left to pay them.

The buildings and units cost the following amounts:
    Farmer costs 10 food and 20 gold, 1 population
    Climber costs 50 food, 50 gold, 50 wood and 1 population
    Woodcutter costs 20 food and 1 population
    House: 50 wood
    Barracks: 230 wood, 230 gold, 100 food
    Church: 250 wood, 250 gold


I decided to add several screenshots do display what a typical game may look like.
![mtn1](https://user-images.githubusercontent.com/14042582/34022547-8c2161e4-e105-11e7-8534-9a6c01fa66b4.PNG)
A nice fresh start.
![mtn3](https://user-images.githubusercontent.com/14042582/34022551-945d1a9c-e105-11e7-9581-112a00bef98e.PNG)
Hm, our village is coming along rather nicely. We'll reach the summit in no time!
![mtn4](https://user-images.githubusercontent.com/14042582/34022553-96a070f6-e105-11e7-8fec-c782c336075e.PNG)
We now have a church. Divine protection feels quite nice.
![deforested](https://user-images.githubusercontent.com/14042582/34022567-9ff6f59e-e105-11e7-81ff-69a1bbb7fc3d.PNG)
Somehow all of the trees were cut down and there is no longer any means of getting food or wood,
![dead](https://user-images.githubusercontent.com/14042582/34022569-a231faca-e105-11e7-9a90-a8cb5c7979eb.PNG)
Which led to the starvation of all the mountain villagers.

Let's start a new game with increased amounts of resources because it is (very) difficult to beat it genuinely.
![capture](https://user-images.githubusercontent.com/14042582/34022572-a5d35c82-e105-11e7-9f5d-09c767686299.PNG)
This village already has a brave climber attempting to summit the peak for his people's honor.
![win](https://user-images.githubusercontent.com/14042582/34022574-a861382a-e105-11e7-8df7-44a70b5474d2.PNG)
He is victorious!



I worked pretty hard on this several months ago, so I hope you enjoy!
