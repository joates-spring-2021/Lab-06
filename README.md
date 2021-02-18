# Lab-06 - Rock, Paper, Scissors
In this lab you will write a Python game to play Rock, Paper, Scissors against the computer.  This exercise is intended to get you introduced to looping for user input, and generally, more familiarity with Python and thinking like a coder.

# Background
Rock, Paper, Scissors is a popular game often played by children, or child-like adults. It is sometimes used as a method of selection similar to flipping a coin or throwing dice to randomly select a person for some purpose.  Of course, this game is not truly random since a skilled player can often recognize and exploit the non-random behavior of an opponent.  For instance, if you notice that your opponent chooses Paper most frequently, you may choose Scissors (which beats Paper) most often in an effort to win. There are many variants of this game.

# Rules of the Game:
The objective of Rock, Paper, Scissors is to defeat your opponent by selecting a weapon that defeats their choice under the following rules:
- Rock smashes Scissors (so Rock wins)
- Scissors cuts Paper (so Scissors win)
- Paper covers Tock (so Paper wins)
- If the players choose the same weapon, neither win and the game is played again

# Requirements
1. Your program shall first choose a computer weapon to play against the user, but not display the weapon until after the user has selected.
2. Your program shall then announce the beginning of the round and use the function input() to prompt the user for their weapon of choice.
3. Your program shall compare the two weapons and determine a winner (or a tie) and the results shall be displayed using print().
4. Your program shall continue looping for user input until the user types "quit" or "exit" or something similar to end the game.
5. Your program shall keep track of wins, losses and ties and display the final "score board" at the end of the game.
6. Rock shall beat Scissors.  Scissors shall beat Paper.  Paper shall beat Rock.

# Specifications
At the beginning of each round your program should ask the user for input.  To make it easier on the user, you can just require R, P, S or Q.  Be prepared to handle upper or lower case entries.  If the user inputs something other than the legal entries, you will have to handle that too.

First, download the project to your local workstation.  I recommend using a source code repository interface such as GitHub Desktop. Start with the template file called main.py. Modify the header to include your own information, and update the code to meet the requirements. When you are satisfied with your changes, commit them to the repository.

After your code is committed to your GitHub repository, go to your account on GradeScope and find the assignment called Lab-06 - JUser Input. Under "Submission Method" select GitHub. You will need to point to the correct repository (called something like joates-223p-spring-2021/lab-06-_your user name_).  You may be asked to link your GitHub account with Gradescope at this time.  Next select the Main branch and press Upload. Gradescope will import your project files from GitHub and automatically grade them.  If you like what you see, you are done.  If not, you can make changes and use the Resumbit button on the bottom right of the Gradescope page to try again.
