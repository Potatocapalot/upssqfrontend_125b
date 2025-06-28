# Initial design brief
Lets imagine your boss have given you the following brief in creating this game  

Create a guess a simple "guess the number" type game. It should choose a random number betweem 1 and 1-100 then challenge the player to the guess the number number in 10 turns. After each turns, the player should be told if there are right or wrong, and if they ae wrong, whether tthe guess was too low or too high, it should also tell the player what numbers the previously got, the game will end onve the number guesses correctly or when they run out of turns but when the game ends the player should be given an option to start playing playing the game again.


Upon looking at this brief, the first thing we need ro do is to start beaking it down into simple actionable task, in as much as a programmers mind as possible.

1.   Generate a random between 1 and 100
2.   Record the turn number the player is on. Start it on 1
3.   Provide player with a way to guess what the number is.
4.   Once a guess has been submitted first record it somewhere so the user can see their previous guesses.
5.   Next, check whether it is the correct number.
6.   If it is the correct number:
        -    display congratulations message.
        -    stop the player from being able to enter more guesses(thsi will mess the game up)
        -    display control allowing theplayer allowing the player to restart the game
7.   If it is wrong and the player has turns left,
        -    tell the player they are wrong and whether their guess was too high or too low
        -    allow them to enter another guess.
8.   If it is wrong and the player has no turn left:
        -    tell the player it is game over
        -    stop the player from being able to enter more guesses.
        -    display control allowing te player to restart the game.
9.   Once the game restarts make sure the game logic and UI are completely reset, then go back to step
