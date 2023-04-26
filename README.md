# ScribblerToo
Use ChatGPT to implement ScribblerToo brushes

## Drawing rules
1. Create a canvas in html5 with a size of 1500x1500.
2. When the mouse is pressed, begin drawing a path and record drawing information (starting point, point set, color, and width).
3. When the mouse moves, continue drawing the path and update the point set in the drawing information.
4. Within a radius of 100 around the last point of the current path, search for all previously recorded drawing information lines.
5. For each found line, randomly select one point and connect it to the last point of the current path with a straight line with a width of 1.
6. When the mouse is released, stop drawing the current path.
7. Repeat steps 2-6 until all paths to be drawn are completed.


## Final result

Code7_test_draw.html

<image src="out1.png"/>

<image src="out2.png"/>