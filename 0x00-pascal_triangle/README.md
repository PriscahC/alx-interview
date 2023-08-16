# 0x00. Pascal's Triangle

Create a function def pascal_triangle(n): that returns a list of lists of integers representing the Pascal’s triangle of n:

Returns an empty list if n <= 0
You can assume n will be always an integer

## Steps
1. Checks if the input n is less than or equal to 0. 
	If it is, then the function returns an empty list.
	else, the function creates a list triangle of lists. 
	The first list in triangle is a list with a single element of 1.

2. Iterates from 1 to n - 1. 
	For each iteration, a new list row is created. 
	The first element of row is 1. 
	The remaining elements of row are calculated by adding the two elements above them in the previous row of triangle.

3. The function then appends row to triangle. Finally, the function returns triangle.

