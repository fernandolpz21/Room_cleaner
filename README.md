# Room_cleaner
## About the Room cleaner
This model made in python simulates a dirty room and a robot cleaning system. The robots strart at the top left tile and start searching for dirty tiles and cleaning them until the room is clean or the number of iterations is exceeded. The robots can move one tile at the time to any of their neighbor tiles.

The model assumes there are no obstacles in the room that could affect robot movement

> You cand find the library documentation here: https://agentpy.readthedocs.io/en/latest/overview.html  

## Observations
The execution time of the program depends on the parameters that are assigned to the program:

- Number of agent robots: The number of agents influences the number of cells they clean because they can execute the action of moving a greater number of times in a row and be able to move around the map more quickly, thus being able to reach more dirty cells. This parameter is represented by the key word numRobots.

- Size of the room: The size of the room to be cleaned influences the execution time because many robots in a small room can finish the execution of the program before the maximum number of executions. This parameter is represented by the key words sizeX and sizeY.

- Dirt Density: The cleaner the room, the faster the robots will finish cleaning the room; this can have different cases, the best case being that all trash is concentrated near the area where the bots spawn, and the worst case being that there is very little trash far from the bot spawn area, in which case they might not finish cleaning the room. This parameter is represented by the key word Dirt density.
