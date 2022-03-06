To use this code you must enter two pairs of values, which are the x-y coordinates of the starting and ending points 
	-The correct way to enter the values are as follows ----> 100, 100
		-ensure there is a space after the comma

Once these values are entered the code will tell the user if the points chosen are within an obstacle. If this is the case the user must select new coordinates
	

If the code is run again then new obstacles will be created, their size and location are selected at random. This was originally done to more easily run through as many scenarios as possible

Once the user has selected two pairs of values for the start/ends points the code will print the cost to go and current node as the nodes are considered

After the program has matched the current node with the goal node a pygame window will be created in which an animation will play showing the obstacles, the frontier of the Dijkstra Algorithm, and the path identified as the most effective route 