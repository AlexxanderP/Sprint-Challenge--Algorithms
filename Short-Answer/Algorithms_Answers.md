#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n\*\*) The total time will increase at a greater rate than the size n.

b) O(n\*\*) The total time will increase at an even greater rate than the size of n.

c) O(n) - Linear- The time will depend on the size of n

## Exercise II

Assuming that floor f is not known, and assuming the floor numbers are known as indexes, I would :

-start from middle floor and drop an egg. if the egg breaks, I would then move to the middle floor of the lower half of floors, else if the egg doesn’t break, I would move to the middle point of the top half.
-Repeat this step until the difference in an egg breaking is the value of one floor height.

Runtime complexity of O(log n)
