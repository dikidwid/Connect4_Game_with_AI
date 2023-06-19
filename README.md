
# Implementation of Minimax and Alpha-Beta Pruning on Connect4 
One problem in traditional Connect Four gameplay is that it can be difficult for human players to predict the best move to make in a given situation. This is because the game has a large number of possible board positions and the optimal move can depend on the future moves of both players.

![Picture1](https://github.com/dikidwid/Connect4-Game-with-AI/assets/92709211/2559210f-50bb-4013-993d-47b663a47666)

To overcome this problem, artificial intelligence techniques such as the Minimax algorithm and Alpha-Beta pruning can be used to help determine the best move to make in any given situation.

The main objective of implementing the Minimax algorithm and Alpha-Beta pruning is to develop efficient decision-making algorithms for two-player, zero-sum games, such as Connect Four. The algorithm is designed to help a computer program to play the game at a level comparable to, or even better than, human players. 

Specifically, the objectives of the Minimax algorithm are:

- To evaluate all possible moves that can be made by both players, up to a certain depth in the game tree.
- To assign a score to each possible outcome, based on how favorable it is for the player making the move.
- To choose the move that maximizes the score for the player making the move.

The objective of Alpha-Beta pruning is to optimize the Minimax algorithm by:
- Reducing the number of nodes that need to be evaluated, thus speeding up the algorithm.
- Pruning parts of the search tree that are guaranteed to lead to suboptimal outcomes, which further reduces the number of nodes to be evaluated.

# What's New?
I've made some changes and improvement with each having its own purpose:
- Timer For Player (User)
The timer feature was added into the code with the purpose of increasing the challenge for the player, by putting them under a time constraint of 5 seconds.

- First Turn Option
The choice on who should start was done to give the player more flexibility in gameplay by allowing them to choose if they would like  to start first or to let the AI start first. To do this we use Python’s TKinter module to create a selectable radio button  that will assign a value to the variable that sets the turn.

Difficulty Options
With our new difficulty option, players can adjust the difficulty of the game to suit their playstyle. This was done by assigning values from the TKinter module to the “Depth” variable that will be used to define the depth of the tree search in the minimax algorithm. There will be three options for difficulty in this game: Easy,Medium,and Hard with each having their own integer value. The easy option will have the lowest integer (1), medium will have (3), and hard will have the largest integer among the three which is (5) this is because in minimax 

# Flowchart

![Flowchart](https://github.com/dikidwid/Connect4-Game-with-AI/assets/92709211/2f938d08-0fce-481d-bfe8-5d3d7a85093b)

# Screenshots

![Picture2](https://github.com/dikidwid/Connect4-Game-with-AI/assets/92709211/8e216b7c-0d7e-4e26-965b-8543da8a91f2)

![Picture3](https://github.com/dikidwid/Connect4-Game-with-AI/assets/92709211/f05b9821-89c0-462f-b093-c74f6cb46b0c)

![Picture4](https://github.com/dikidwid/Connect4-Game-with-AI/assets/92709211/d54f36b9-8b75-40b2-83f5-9cf63105ce8d)

![Picture6](https://github.com/dikidwid/Connect4-Game-with-AI/assets/92709211/aa872c77-1f6d-4b60-8b83-8c5b8dd46fbb)

# References
Video walkthrough on programming this game: https://youtu.be/UYgyRArKDEs
