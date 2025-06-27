# A random spider walk
This is my first time using Monte Carlo simulation. Wish me luck :D.

So, this is the problem:

>Every minute, the spider moves at an angle taken at random uniformly between 0 and 360 degrees, at a distance taken at random uniformly between 0 and 2m.
>
>The spider starts at coordinates (0, 0) and my place can be represented by the area determined by the square delimited by upper-left corner (10, 10) and lower-right corner (15, 6) (unit is meter)
>
>What's the probability the spider is at my place after 240mn?

For this problem we are going to simulate a very large quantity of spiders. Check how many of them arrive at the square that we are looking for. And theorically this will result in a relation that is very close to the probability.

To simulate these spiders we have to understand what implies moving at a random angle. First of all, we are going to be working with x and y coordinates. So moving at an angle has to be tranformed into the horizontal movement and the vertical movement. We can get those values using the sin and cos functions. Getting the formulas movement\*sin(angle) = y_movement and movement\*cos(angle) = x_movement.

After getting these two formulas we only need to use random values and we will be next to finishing. Simulating a large quantity of spiders and checking the ones that got into the house would be the last steps to finding the probability of the spider being in the square after 240 minutes.

After doing it I thought making a visual representation would be the best way to understanding the proces that we are going through.

![Simulation of 100 spiders](/100_spiders.png)
![Simulation of 1000 spiders](/1000_spiders.png)
![Simulation of 10000 spiders](/10000_spiders.png)
