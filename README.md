# LotteryGame
Simulation of a lottery game like the Irish national lottery. 

Program to create a Lottery Game, including options for the user to control the game via a menu.

User can select 6 options from the Main Menu:
1: to select their lottery numbers 
2: to display their chosen numbers
3: to sort their chosen numbers in ascending order
4: to see if they have won with their chosen numbers
5: to display the frequency of their chosen numbers being selected in each round of the game, until they quit and the game ends
6: to exit or quit the game.

Rules/Controls:
- The program should return to the Main Menu after each option (1-5) has been run.
- The user cannot enter options 2-5 if they have not entered 6 valid numbers:
        - within the range 1 to 42
        - with only one occurence of any single number
- The frequency of the user's chosen numbers are remembered on each round of the game, until exit. 
- There is no limit on the number of rounds that can be played. 
