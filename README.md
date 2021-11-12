# Solved problems in stochastic calculus

## Problem of 2D random walk
An ant leaves its anthill in order to forage for food. It moves with the speed of 10 cm per second, but it doesn't know where to go, therefore every second it moves randomly 10 cm directly north, south, east or west with equal probability.

1) If the food is located on east-west lines 20 cm to the north and 20 cm to the south, as well as on north-south lines 20 cm to the east and 20 cm to the west from the anthill, how long will it take the ant to reach it on average?

2) What is the average time the ant will reach food if it is located only on a diagonal line passing through (10 cm, 0 cm) and (0 cm, 10 cm) points?
Can you write a program that comes up with an estimate of average time to find food for any closed boundary around the anthill? What would be the answer if food is located outside the boundary defined by 
![equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%28x-2.5%29%5E2%7D%7B30%5E2%7D%20&plus;%20%5Cfrac%7B%28y-2.5%29%5E2%7D%7B40%5E2%7D%20%3C%201) (lengths in cm) in coordinate system where the anthill is located at (x = 0 cm, y = 0 cm)? Provide us with a solution rounded to the nearest integer.

(For solution, see `stopping_time_2d_random_walk.ipynb`)
