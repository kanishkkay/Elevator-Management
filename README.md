# Elevator-Management
This is a java program used to operate elevators.
By default, it is defined that lift will not operate if the weight exceeds 560kgs ie. 8 persons with 70kgs each. In order to test this, i've added a random number generator function upto 560kgs of range and if the weight exceeds that, it will show a popup asking to reduce the no of persons in the lift.
In order to make the program functional and test it, i've used random numbers between 0 & 10 in order to simulate the floors for both the positions where in: 
a) the floor from where the lift's call is generated.
b) the floor where lift is actually present is generated.
The program is a .jar file but i'm attaching code too for your consideration.
The program  will handle a configurable number of lifts, all controlled by the same 2 buttons on each floor by using the concept of priority queue wherein the availabilty of lift corresponding to the selection of floor of the user is determined and operated accordingly.
