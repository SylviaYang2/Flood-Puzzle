# Flood-Puzzle

## Rules

The puzzle game Flood is one of Simon Tatham's collection of GUI games. It is played on a W×H rectangular grid of square cells. Every square is colored from a set of available colors. We'll use the term **active region** to refer to the set of grid cells having the same color as the **upper-left cell and orthogonally reachable** from that square. A cell is orthogonally reachable from a square S having color C if it can be reached by moving one square at a time up, down, left, or right starting from S and moving only to squares of color C.

Each time the player clicks on a square with a color different from that of the active region, all the cells currently in the active region take on that color. So if there are cells of this color adjacent to the active region, they get added to the active region.

The player's goal is to make all cells the same color by clicking a series of cells. The program sets an **upper limit** on the number of moves, depending on its own determination of how many moves are needed.

As an example, consider starting from the board labeled 0/7 below. The subsequent numbered boards that follow result from clicking on cells whose colors are, respectively, green, yellow, red, green, yellow, blue, and red. This results in an all-red board in 7 moves.

![image](https://user-images.githubusercontent.com/83314726/184458725-38f32260-a568-4e92-bc3e-f74effd54671.png)
![image](https://user-images.githubusercontent.com/83314726/184466636-71b8f48c-d1a2-4ef2-9530-16d12d58dfdb.png)
![image](https://user-images.githubusercontent.com/83314726/184466639-3cc3ad2e-fbf1-4489-ab69-2f9146d27b36.png)
![image](https://user-images.githubusercontent.com/83314726/184466640-f7e928e2-ed5f-4886-913f-3d83bc174a27.png)
![image](https://user-images.githubusercontent.com/83314726/184466641-afd1aac5-b5e7-4ab1-90bf-58a80d790dec.png)
![image](https://user-images.githubusercontent.com/83314726/184466645-107e1b8d-c34c-43b1-82ef-fde592915a43.png)
![image](https://user-images.githubusercontent.com/83314726/184466646-78d0955b-12bd-48ef-84b3-83179b5fdbe4.png)
![image](https://user-images.githubusercontent.com/83314726/184466647-aaad92b6-79cc-4984-b75d-03b4ca33c230.png)

