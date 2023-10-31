# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
The most difficult part was creating the has_won function. It involvedthe most code and makign the diganoal wins were harder due to there being less of a pattern.

2. Explain how you would add a computer player to the game.
 I would probably use a randomizer to pick the spots for the computer or have it go to a specific set of spots every time. It might not lead to the best move but it allows for a computer to play. It would not matter if the randomizer chooses a spot where something has already been placed as it is an invalid move and would allow the computer to continue until it finds a vacant spot.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
First if the computer is starting I would have it choose a corrner or if it is going 2nd I owuld try to make it take the middle. Then from their the best moves would probably first include trying to make the computer stop potential wins by the other player and if it doesn't spot any potential wins then it could place its move on a tile where it can make win on the next turn. Since I believe humans like taking corners fist since its the easiest way to win, having the computer set up a counter stratagey would be the best option for it to win. 