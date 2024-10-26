
The code is divided into multiple functions; each function performing some specific task.

result(board,a) - returns the state of the board after performing a move
actions(board) - returns all the possible places where player can make a move from state of the board. (it checks empty box in the matrix and returns it's index as an action)
check_wins(board,player) - returns the true if the player passed wins in the given state of the board. It checks all the 3 condtion diagonal win, col win, and row win.
check_draw(board)-  it checks if the board is in draw state.
utility(board) - returns the utility value of the board.



