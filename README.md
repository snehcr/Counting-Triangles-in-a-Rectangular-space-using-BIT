# Counting Triangles in a Rectangular space using BIT
 counting the no of rectangles in a space using binary index tree
Given a 2D plane, respond to Q queries, each of the following type: 

Insert x y – Insert a point (x, y) coordinate.
Triangle x1 y1 x2 y2 – Print the number of triangles that can be formed, by joining the points inside the rectangle, described by two points (x1, y1) and (x2, y2), (x1, y1) is the lower-left corner while (x2, y2) is the upper right corner. We will represent it as {(x1, y1), (x2, y2)}.(Include the triangles with zero areas also in your answer)
Example: 
 



In the red rectangle there are 6 points inserted, 
when each of them is joined with a line with every
other point, in all 20 triangles will be formed.
