This is a Tic-Tac-Toe game with computer playing against you , it's implemented using MiniMax Algorithm which allows the program to choose best action (move) from sets of all possible actions by going till the end of each action (move) and seeing where that move will lead to in the end if the opponent played the best move possible.

The code is divided into multiple functions; each function performing some specific task.

result(board,a) - returns the state of the board after performing a move
actions(board) - returns all the possible places where player can make a move from state of the board. (it checks empty box in the matrix and returns it's index as an action)
check_wins(board,player) - returns the true if the player passed wins in the given state of the board. It checks all the 3 condtion diagonal win, col win, and row win.
check_draw(board)-  it checks if the board is in draw state.
utility(board) - returns the utility value of the board.



