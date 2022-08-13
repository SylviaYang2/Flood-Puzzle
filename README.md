# Flood-Puzzle
 It is played on a W×H rectangular grid of square cells. Every square is colored from a set of available colors. We'll use the term active region to refer to the set of grid cells having the same color as the upper-left cell and orthogonally reachable from that square. A cell is orthogonally reachable from a square S having color C if it can be reached by moving one square at a time up, down, left, or right starting from S and moving only to squares of color C.

Each time the player clicks on a square with a color different from that of the active region, all the cells currently in the active region take on that color. So if there are cells of this color adjacent to the active region, they get added to the active region.

The player's goal is to make all cells the same color by clicking a series of cells. The program sets an upper limit on the number of moves, depending on its own determination of how many moves are needed.

As an example, consider starting from the board labeled 0/7 below. The subsequent numbered boards that follow result from clicking on cells whose colors are, respectively, green, yellow, red, green, yellow, blue, and red. This results in an all-red board in 7 moves.

![image](https://user-images.githubusercontent.com/83314726/184458725-38f32260-a568-4e92-bc3e-f74effd54671.png)
