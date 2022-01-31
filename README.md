# Overlapping-Ellipses-UKA

In this problem you will use a pseudo random numbers to estimate the area of two overlapping ellipses.
An ellipse is a curve in a plane surrounding two focal points such that the sum of the distances to the two
focal points is constant for every point on the curve. – Wikipedia.
Create a Point class that takes the x and y coordinates of the point:
 p1 = Point(2,3)
 p2 = Point(4,3)
 
Create an Ellipse class that takes two points and the width of the long axis:
 e1 = Ellipse(p1,p2,4)
 
Write a function that takes two ellipses and returns the area of the overlap:
 overlap = computeOverlapOfEllipses(e1,e2)
 
