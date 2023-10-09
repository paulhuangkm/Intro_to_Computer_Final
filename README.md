# Tower Defense Game

## Author
- Paul Huang

![](./img/f1)
## Game Introduction:
In this game, the players defend the castle from the enemies by building defensive cannon towers. There are 25 waves of attacks, and the damage and hit points of enemies increase through waves. There are three roads and eight positions for players to build towers. Players can press numbers 1 to 8 to select a position/tower to see the info of that position/tower on the upper right, including the location (1 to 8), cost, level, and type (Cannon if there is a tower or None if it is empty) of the position/tower. After being built, towers fire cannonballs at the enemies if they are close enough. Players need to spend money to build/upgrade towers, and both the cost and the damage of a tower increases as the level of the tower increases. The game displays the amount of money on the upper left with the wave count. Different amounts of enemies (maximum of 15 enemies in a wave) will come out from different roads in different waves. The hit point of a soldier is shown above its head, and the soldier dies if its hit point is less than or equals 0. If all of the enemies die, the game continues automatically to the next wave. Enemies walk toward the castle and if a soldier gets near the castle, it starts attacking. The health of the player is shown on the left, and a player loses if his/her health is smaller or equals 0. Players can pause the game by pressing P, and get back into the game by pressing P again. After the game ends (either the player dies or finishes the 25 waves), the screen shows the score of that game and goes back to the main menu (the highest score is shown on the upper left of the main menu).

![](./img/f2)

## Game Instructions:
- In main menu:
    - Press enter to start
    - Press Q to quit
- In game:
    - Press 1~8 to select position/tower
    - Press B to build/upgrade towers (Prints “Not enough money” if the player does not have enough money)
    - Press P to pause/continue
- Game ending:
    - The screen shows player’s score and goes back to main menu

## Short Story About the Map of My Mini Game:
The roads in the game were not designed to be straight lines at first, and there was a forest around the map when I first drew it (see Figure 8). However, since the forest and curvy roads have no obvious pattern to draw, it would use up too much ROM space, so I modified the map to the one you see today.

![](./img/f3)

When I first started writing the game, I thought the most difficult part of the project is writing the program. After I finally finished the game and tried to play it, I found out that the most difficult part is actually trying to balance the game. From the health of players, the cost of towers, and the length of roads to the hit point and damage of enemies, it really takes a bunch of work to make the game both winnable and intriguing at the same time.

Another interesting part of the project was translating bitmap images into Jack language. It took quite some time to understand the header format of bitmap. I used C for reading and translating the file.

## Demo Link
[Youtube](https://www.youtube.com/watch?v=UtlRthFu4qo)

## References
- [Nand2Tetris](https://www.nand2tetris.org/)
