## General Info

Simple Maze Generator and game written in TI-BASIC.

Pretty self explanatory, you are a red dot on a maze and your goal is to get to the green mark on it. 
Use the arrow keys to move.

Use *MAZEGEN* to generate a maze and only after the maze is genetared use *MAZEPLAY*. If you for some reason want to do a break mid maze you can abort the code execution with the 'ON' button. Then if you execute *MAZEPLAY* again you continue from your wherever your position was before aborting execution.

NOTES:
* The max width size is 20.
* The generation of a 20x20 maze may take up to 2 minutes.

## Some Pictures
![8x8 Maze](https://github.com/Ze-Rato/Maze-TI-BASIC/assets/132148561/375ff258-84c0-4501-8b47-c8a3d4fd6da2)

![20x20 Maze](https://github.com/Ze-Rato/Maze-TI-BASIC/assets/132148561/58544ee1-38f5-47e5-97e9-10c70e189ce2)

![Won](https://github.com/user-attachments/assets/7de345e2-ad8a-4a15-9504-997c7d6febf5)


## Upadtes and Patches

|    Version    | Date of Realease | Changes Description |
| ------------- | ------------------- | -------- |
| 1  | 06/07/2024 | -Launch  |
| 1.1 | 07/07/2024 | -Added Playability<br> -Fixed the display to be a square instead of a rectangle<br> -Optimized some code on *MAZEGEN*<br> -Changed 'player dot' size to be smaller on bigger mazes so it doesn't overlap with the walls |
| 1.2 (Current) | 13/07/2024 | -Restricted the choice of the winning point coordinates to avoid short games<br> -Removed some unecessary if statments on *MAZEGEN*<br> -Some minor display changes such as the border color<br> -Added options to *MAZEPLAY* when the player wins the game (1. Generate another maze; 2. Play using the same maze but change the win point; 3. Exit). While option 2 makes mazes reusable it's worth noting that it might only be interesting to use it on big mazes since those have more room for randomness|


## To do
* Make see solution feature
* On the exit option reset to default the graph settings and delete now unecessary data like the maze matrix and the HIST list
