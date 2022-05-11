# PyScript Mancala AI
This is just a simple AI for the game of Mancala built in Python. It uses minimax with alpha-beta pruning to find the best move.
This project is to test out how to use PyScript to implement some Python projects in a website. It is not a complete project.

# How to use
- This game was built to be counter-clockwise. To play, click on the bottom row to select which pit you want to move from.
- After you make your move, it will rotate the board 180 degrees and say that it's player 2's turn. You play both player one and player two. Without animation, it can confusing who's turn it is.
- On the bottom, it says, "Best moves - " and then it shows the expected score for a given with each corresponding pit by index. The score is the difference between the player's score and the opponent's score. The best move would be the argmax of the list.
- To restart, just reload the page.