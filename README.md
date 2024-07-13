## General Info

Simple Maze Generator written in TI-BASIC.

Pretty self explanatory, you are a red dot on a maze and your goal is to get to the green mark on it. 
Use the arrow keys to move.

NOTES: 
* The max width size is 20.
* The generation of a 20x20 maze may take up to 2 minutes.

## Some Pictures
![8x8 Maze](https://github.com/Ze-Rato/Maze-TI-BASIC/assets/132148561/375ff258-84c0-4501-8b47-c8a3d4fd6da2)

![20x20 Maze](https://github.com/Ze-Rato/Maze-TI-BASIC/assets/132148561/58544ee1-38f5-47e5-97e9-10c70e189ce2)

![Won](https://github.com/Ze-Rato/Maze-TI-BASIC/assets/132148561/4d91dc92-24e8-41a9-af1c-86236a73b5c6)


## Upadtes and Patches

|    Version    | Date of Realease | Changes Description |
| ------------- | ------------------- | -------- |
| 1  | 06/07/2024 | -Launch  |
| 1.1 | 07/07/2024 | -Added Playability<br> -Fixed the display to be a square instead of a rectangle<br> -Optimized some code on MAZEGEN<br> -Changed 'player dot' size to be smaller on bigger mazes so it doesn't overlap with the walls |
| 1.2 (Current) | 13/07/2024 | -Restricted the choice of the winning point coordinates to avoid short games<br> -Removed some unecessary if statments on MAZEGEN<br> -Some minor display changes such as the border color<br> -Added options when the player wins the game (1. Generate another maze; 2. Play usinng the same maze but change the win point; 3. Exit). While option 2 makes mazes reusable it's worth noting that it might only be interisting to be used on big mazes since those have more room for randomness|


## To do
* Make see solution feature
