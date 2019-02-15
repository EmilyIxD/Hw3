# Hw3
Homework for week 3

What code draws the blades of grass?
Line 11 draws the blades of grass - line(x, height-10, x+random(-10, 10), height-10-random(h))

What code makes the "lawnmower" come by? How often does it come by?
Lines 21-24 make the "lawnmower" come by:   
if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-100);
    h = 10;
This is placing a white rectangle over the grass at random intervals when the height is greater than 0.999.

What's the point of the h variable?
It sets the starting height of the grass.

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
The first -10 is telling the program where to start drawing the grass and the second -10 is saying how high the first line of grass should be/the maximum starting height.
