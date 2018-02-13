# ProtoBattleship
The grid: The grid will be played on a 6x6 square, with letters for columns and numbers for rows. 

Selecting a ship: The program begins with a menu displaying the three different ship types (Corvette, Frigate, and Ironclad) and their stats, asking the user to select their ship. Once the user's ship has been selected, the program will ask the user to select a ship for the computer. Both the user and computer are allowed to select the same ship type. 

Placing the ship: For simplicity's sake, the user's ship will be placed at coordinates (A, 1) and represented with a 'c', 'f', or 'i' on the grid. The computer's ship will be placed at (F, 6) and represented with a 'C', 'F', or 'I'. Both players will see the grid and thus, will know where all ships are located. 

Gameplay: Gameplay will be turn based. On the player's turn, he can choose to either move or attack. The distance a ship can move will depend on its speed attribute. A ship can only attack if the target is within range. Every attack will have a probability of a hit or miss. The game will tell the player whether the shot was successful. A successful shot will deplete a portion of the target ship's health. Gameplay will continue until the one of the ships has depleted its health. If the user wins, a victory message will be printed to the grid. If the user loses, a defeat message will be printed to the grid. 

Computer behaviour: The computer will continue moving its ship (in random directions?) until the player ship is in range. Once in range, the computer will continue to attack until the player moves his ship out of range. At this point, the computer ship will resume moving around. 
# Unity Notes

I will be watching Brackey Unity beginner's tutorial

https://www.youtube.com/watch?v=j48LtUkZRjU&list=PLPV2KyIb3jR5QFsefuO2RlAgWEz6EvVi6
Add youtube video title you are watching and summarize any significant information that can be used
Add timestamps to significantly important chapters of a video


end of Unity Notes
# Revision History
0.01 - Got 2D board uploaded and moving ship works

0.02 - Can move ship with speed of one limit from the center of board and the four corners. Test the four sides

0.03 - See array of ship

0.03 - We assumed we needed a char of ships. We only needed a getter function for ships's rep and set it equal to the char array's values
       We also created instances of ship in the main and tested that the speed works for specific ships we're passing in the moveONE function                 
       correctly.

2/11 v 0.05 - CheckRange function works. Attack function works. Simplify check range too.

end
