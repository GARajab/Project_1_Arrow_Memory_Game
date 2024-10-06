# Pseudocode of the Arrow Game

### Story is the game will give the player multiple numbers of arrows (6) with different directions like (up,down,right,up,left,down) for a small time and they will be turned up side down and let the player take his time to guess and try to remember the directions.

- **Player** will depend on his memory to try to get all directions of the flipped over cards correctly
- **Score** is counted by arrows one correct by one correct not by the full arrows correct
  **_(means if the player got more than 1 and less than and equal to 3 cards out of 6 correct his score will be 3 points even if he got one card correct else if more than 3 and less than and equal 6 will git 5 points else he will git (0)) rounds will be there max 5 rounds then score will be counted at the end of the game time_**
- **Some speed** will be there each two time correct the speed will be increased till max 6 times correct for example **_(2 speed will be 1, 4 speed will be 2, 6 speed will be 3)_** - **The player will change his cards by using two directions arrow** under each card, **Each** click will change the direction of the arrow (up,right,down,left,again up)
- **There will be tow modes** an **_easy_** and an hard mode, easy will git all his boxes filled with **up direction** box and there is **no time limit**, **_Hard_** will get all boxes filled with arrows but **each arrow is in different direction** and there will be a **limited time per round**

# Code side

1. I will make 6 divs will contain the random directions arrows (PC ARROWS).
2. I will make 6 divs will contain the Player arrows boxes (Player ARROWS), each player boxes there are 12 divs to make small two boxes will handel the change of player directions.
3. I will make three variables handel the score , how many box correct and the the last one will contain the numbers of the rounds.
4. I need to have two arrays one for (random pc arrows) and the other is the player array.
5. Will use loop to loop throw the two arrays to get the score how many correct and how many incorrect.
6. Will make <button>Reset</button> to reset the game and the full values except the player score.
7. I will make a new div containing a switch to toggle between easy mode and hard mode.
8. I have to have an if condition to differ between the two scenarios (all boxes are correct with no empty box means all ids (player and pc are matched (each array of pc and player are identical)), And the other if is some boxes empty(innerHTML= "") and how many of filed ones are correct or no)
9. I need a function to randomizes the pc boxes
10. I need a function to check the player boxes
11. I need a function to count scores and other for rounds and correct/incorrect player boxes.
12. I need a function to reset the full game except the score after each round.
