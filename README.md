# TicTacToepy
Tic tac toe Game using python 
PROBLEM ANALYSIS CHART 

1. INPUT 
  a. The exact position (row and column ) from user from the by default set player X first 
     then accordingly for player O
     
2.Process 
  a. According to the rules of the TicTacToe game the alternate  row column entry by both the players is facilated 
  b. Then the user defined functions can be used to check the  2 digonal as well as row and column entries after every user entry and then display 
     the array if no any match but if matched return the name of the player won 
3.Output 
- - X 
O - - 
- - - 
Enter row and column numbers to fix spot: 1 1
Player O turn
X - X 
O - - 
- - - 
Enter row and column numbers to fix spot: 3 3
Player X turn
X - X 
O - - 
- - O 
Enter row and column numbers to fix spot: 1 2
Player X wins the game!

PSEUDOCODE 
1. Import the random module having inbuilt function used for switching player 1 and two for entry turns one by one  accordingly 
2. Array with '-' as common element can be written using nested for loops or using (import numpy ) direct array creation can be done
   Here the name of the array is 'board' which is actually the member of class ticTacToe  
3. Then a user defined function is used to pass the above created array as an argument to the function 
4. get_random_first_player(self) function is used to control the switching nature of the program using be default keywords of random module
5. def fix_spot(self, row, col, player) is used to accept the user entries and place it accordingly in the tacktactoe plot 
6. def is_player_win(self, player) is used to check for winning conditions for the game using global variable "win" 
   a.The row and column  wise check  using two for loops as usualy prefered
   b.The left digonal ==> check where inside nested for loop ==> board[i][i]==player same entry since left digonal check 
   c.the right digonal check ==> board[i][n - 1 - i] != player
   RETURN The name of the player whose entries match above patterns 
   ELSE 
   Return Draw  if the array is also complete but the entries doesnt pass array matching conditions
7. Then consider user input and call the functions finally in the same order of definations mentioned  above

Thus this game developed using the class concepts and two modules random as well as numpy 
It uses all the code coupled inside the user defined function definations 

!!!THANKYOU!!!

  
  
